# SetSpawnPositionPacket

**ID: 43**  
**Purpose: When a player logs in or the SetWorldSpawnCommand is used this is sent from the server to the client. Does not change when using a bed, that is a separate packet (RespawnPacket)**  

see RespawnPacket

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Spawn Position Type</td><td>enum SpawnPositionType</td></tr>
<tr><td>Block Position</td><td>X</td></tr>
<tr><td>Dimension type</td><td>value</td></tr>
<tr><td>Spawn Block Pos</td><td>X</td></tr>
</tbody></table>