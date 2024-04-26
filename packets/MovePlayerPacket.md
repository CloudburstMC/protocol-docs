# MovePlayerPacket

__ID: 19__

This is the packet that keeps track of position, rotation, head rotation, if the actor is on ground, and if it is riding something.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Player Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Rotation</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
<tr><td>Y-Head Rotation</td><td>float</td></tr>
<tr><td>Position Mode</td><td>byte</td></tr>
<tr><td>On Ground</td><td>bool</td></tr>
<tr><td>Riding Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Dependency on 'Position Mode == Teleport'</td><td><b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Teleportation Cause</td><td>int</td></tr>
  <tr><td>Source Actor Type</td><td>int</td></tr>
  </tbody></table></td></tr>
<tr><td>Tick</td><td><table><tbody><tr><td>unsigned varint64</td><td>Should be the tick we last processed from PlayerAuthInputPacket or 0 if we're not doing server authoritative movement</td></tr></tbody></table></td></tr>
</tbody></table>