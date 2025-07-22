# StructureBlockUpdatePacket

**ID: 90**  
**Purpose: Structure Block Update**  

After the client makes changes in the Structure Block Screen we tell the server to update based off of that. This only sent when you close the UI.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Block Position</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
<tr><td>Structure Data</td><td><a href="../types/StructureEditorData.md">StructureEditorData</a></td></tr>
<tr><td>Trigger?</td><td>bool</td></tr>
<tr><td>IsWaterlogged</td><td>bool</td></tr>
</tbody></table>