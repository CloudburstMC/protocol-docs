# BiomeDefinitionListPacket

**ID: 122**  
**Purpose: Biome Definition List**  

On world start, send clients the info for all available biomes.Sends the whole list of the biomes from server to the client at the start of the game from _sendLevelData()

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Map of Biome names to data</td><td><b>Map Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>String Index to Biome name</td><td><a href="../types/short.md">short</a></td></tr>
  <tr><td>Biome Definition Data</td><td><a href="../types/BiomeDefinitionData.md">BiomeDefinitionData</a></td></tr>
  </tbody></table></td></tr>
<tr><td>String list</td><td><a href="../types/BiomeStringList.md">BiomeStringList</a></td></tr>
</tbody></table>