# CraftingDataPacket

__ID: 52__

Sent from the server on level startup to send all recipes to the client. As of this writing it's a ~150k packet.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Crafting Entries</td><td><b>Array Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Crafting Entry</td><td><a href="../types/CraftingDataEntry.md">CraftingDataEntry</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Potion Mixes</td><td><b>Array Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Potion Mix Entry</td><td><a href="../types/PotionMixDataEntry.md">PotionMixDataEntry</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Container Mixes</td><td><b>Array Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Container Mix Entry</td><td><a href="../types/ContainerMixDataEntry.md">ContainerMixDataEntry</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Material Reducers</td><td><b>Array Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Material Reducer Entry</td><td><a href="../types/MaterialReducerDataEntry.md">MaterialReducerDataEntry</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Clear Recipes</td><td>bool</td></tr>
</tbody></table>