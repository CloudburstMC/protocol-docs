# SetSpawnPositionPacket

**ID: 43**  
**Purpose: Set Spawn Position**  

When a player logs in or the SetWorldSpawnCommand is used this is sent from the server to the client.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Spawn Position Type</td><td>varint</td></tr>
<tr><td>Block Position</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
<tr><td>Dimension type</td><td>varint</td></tr>
<tr><td>Spawn Block Pos</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
</tbody></table>