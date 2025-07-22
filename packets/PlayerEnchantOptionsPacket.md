# PlayerEnchantOptionsPacket

**ID: 146**  
**Purpose: PlayerEnchantOptionsPacket**  

This packet is sent from the server whenever a player rerolls a new set of enchantment options from the enchantment table

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Options</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Cost</td><td>unsigned varint</td></tr>
  <tr><td>Enchants</td><td><a href="../types/ItemEnchants.md">ItemEnchants</a></td></tr>
  <tr><td>Enchant Name</td><td>string</td></tr>
  <tr><td>Enchant Net Id</td><td><a href="../types/TypedServerNetId_RecipeNetIdTag.md">TypedServerNetId&lt;struct RecipeNetIdTag,unsigned int,0&gt;</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>