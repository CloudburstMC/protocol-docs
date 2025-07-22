# ResourcePackStackPacket

**ID: 7**  
**Purpose: Resource Pack Stack**  

This is sent to the client in response to a ResourcePackClientResponsePacket which is fired when MinecraftGame starts.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Texture Pack Required</td><td>bool</td></tr>
<tr><td>Add-On List</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>ID</td><td>string</td></tr>
  <tr><td>Version</td><td>string</td></tr>
  <tr><td>Sub Pack Name</td><td>string</td></tr>
  </tbody></table></td></tr>
<tr><td>Texture Pack List</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>ID</td><td>string</td></tr>
  <tr><td>Version</td><td>string</td></tr>
  <tr><td>Sub Pack Name</td><td>string</td></tr>
  </tbody></table></td></tr>
<tr><td>Base Game Version</td><td><a href="../types/BaseGameVersion.md">BaseGameVersion</a></td></tr>
<tr><td>Experiments</td><td><a href="../types/Experiments.md">Experiments</a></td></tr>
<tr><td>Include Editor Packs</td><td>bool</td></tr>
</tbody></table>