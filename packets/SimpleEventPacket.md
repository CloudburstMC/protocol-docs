# SimpleEventPacket

**ID: 64**  
**Purpose: This packet is used for enabling/disabling commands and for unlocking world template settings (both unlocking UI buttons on client and the actual setting on the server).**  

This is fired from the client to the server and a SetCommandsEnabledPacket is sent back when enabling commands.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Type</td><td>enum Subtype</td></tr>
</tbody></table>