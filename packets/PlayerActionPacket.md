# PlayerActionPacket

__ID: 36__

Sent from the client whenever the player performs an action (dashing, undashing, use an item, mine/hit, use a block, etc).

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Player Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Action</td><td>varint</td></tr>
<tr><td>Block Position</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
<tr><td>Result Pos</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
<tr><td>Face</td><td>varint</td></tr>
</tbody></table>