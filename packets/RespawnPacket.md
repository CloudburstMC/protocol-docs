# RespawnPacket

**ID: 45**  
**Purpose: Sent as a handshake between the client and server to respawn the player.**  

For some reason each respawn 1 packet is sent from the client and 3 are sent from the server.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Position</td><td>X</td></tr>
<tr><td>State</td><td>enum PlayerRespawnState</td></tr>
<tr><td>Player Runtime Id</td><td>Actor Runtime ID</td></tr>
</tbody></table>