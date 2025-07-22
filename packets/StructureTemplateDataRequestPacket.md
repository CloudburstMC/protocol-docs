# StructureTemplateDataRequestPacket

**ID: 132**  
**Purpose: Structure Data Request**  

Used to request structure information from a server.How we want to get our structure: by capturing what is live in the world,

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Structure Name</td><td>string</td></tr>
<tr><td>Structure Position</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
<tr><td>Structure Settings</td><td><a href="../types/StructureSettings.md">StructureSettings</a></td></tr>
<tr><td>Requested Operation</td><td>byte</td></tr>
</tbody></table>