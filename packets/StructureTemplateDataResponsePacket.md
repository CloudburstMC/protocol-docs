# StructureTemplateDataResponsePacket

**ID: 133**  
**Purpose: This is used in exporting from load, exporting from save, and querying saved structures from structure blocks.**  

The client sends a packet to the server, from there the structure is built and then put into a Tag where it is sent back to the client, from there you can view the structure in the Structure Block Screen. Currently this functionality is completely disabled and does nothing. Used to reply to a request for structure information.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Structure Name</td><td>string</td></tr>
<tr><td>Structure's NBT</td><td></td></tr>
<tr><td>Response Type</td><td>enum enum StructureTemplateResponseType</td></tr>
</tbody></table>