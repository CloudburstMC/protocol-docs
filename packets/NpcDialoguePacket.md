# NpcDialoguePacket

**ID: 169**  
**Purpose: NpcDialoguePacket**  

Sent from the server to client when remote firing an NPC dialogue window for a client.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Npc Id Raw Id</td><td><table><tbody><tr><td>unsigned int64</td><td>The ActorUniqueID of the NPC being remote fired</td></tr></tbody></table></td></tr>
<tr><td>Npc Dialogue Action Type</td><td>varint</td></tr>
<tr><td>Dialogue</td><td><table><tbody><tr><td>string</td><td>The text to be displayed to the client</td></tr></tbody></table></td></tr>
<tr><td>Scene Name</td><td><table><tbody><tr><td>string</td><td>The scene the data has been pulled from for the client to reference</td></tr></tbody></table></td></tr>
<tr><td>Npc Name</td><td><table><tbody><tr><td>string</td><td>The name of the NPC to be displayed to the client</td></tr></tbody></table></td></tr>
<tr><td>Action JSON</td><td><table><tbody><tr><td>string</td><td>The JSON string of the buttons/actions the server can perform. The server is still authoritative on what actions can be performed</td></tr></tbody></table></td></tr>
</tbody></table>