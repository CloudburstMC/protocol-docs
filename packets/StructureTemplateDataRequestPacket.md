# StructureTemplateDataRequestPacket

**ID: 132**  
**Purpose: Used to request structure information from a server.**  

This is used to kick off the process of loading and returning a structure in a Tag from the server back to the client. Currently this functionality is completely disabled and does nothing.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Structure Name</td><td>string</td></tr>
<tr><td>Structure Position</td><td>X</td></tr>
<tr><td>Structure Settings</td><td>Structure Palette Name</td></tr>
<tr><td>Requested Operation</td><td>enum enum StructureTemplateRequestOperation</td></tr>
</tbody></table>