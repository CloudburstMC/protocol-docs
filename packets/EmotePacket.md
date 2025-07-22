# EmotePacket

**ID: 138**  
**Purpose: Emote Packet**  

A client sends this to the server to notify other clients about the emote.Sent in both directions; by client to request that an emote is played and then from the server to the clients

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Actor Runtime Id</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Emote Id</td><td>string</td></tr>
<tr><td>Emote Length Ticks</td><td>unsigned varint</td></tr>
<tr><td>Xuid</td><td>string</td></tr>
<tr><td>PlatformId</td><td>string</td></tr>
<tr><td>Flags</td><td>byte</td></tr>
</tbody></table>