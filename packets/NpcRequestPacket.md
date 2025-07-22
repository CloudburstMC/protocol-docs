# NpcRequestPacket

**ID: 98**  
**Purpose: Used for a number of interactions with the NPC Component**  

A request is made from the client during an interaction with an NPC then the request is processed by the server. Actor MUST have the NPCComponent to be handled.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>NPC Runtime ID</td><td>Actor Runtime ID</td></tr>
<tr><td>Request Type</td><td>enum NpcRequestPacketPayload RequestType</td></tr>
<tr><td>Actions</td><td>string</td></tr>
<tr><td>Action Index</td><td>unsigned byte</td></tr>
<tr><td>Scene Name</td><td>string</td></tr>
</tbody></table>