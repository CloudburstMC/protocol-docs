# SetActorMotionPacket

__ID: 40__

This is technically sent by both server and client, but only the client is receiving any packets.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Motion</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Server Tick</td><td>unsigned varint64</td></tr>
</tbody></table>