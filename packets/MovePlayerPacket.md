# MovePlayerPacket

**ID: 19**  
**Purpose: Move Player**  

For client authoritative and server authoritative movement modes, it is only intended as a client-bound packet. It forces the player to a specified position with slightly different behavior depending on the position mode. For similar packets that move the player, see also: - CorrectPlayerMovePredictionPacket (server authoritative) - SetActorMotionPacket

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Player Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Rotation</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
<tr><td>Y-Head Rotation</td><td><table><tbody><tr><td>float</td><td>Rotation in degrees of the head. Almost always matches Y rotation. The server authoritative equivalent of this is PlayerAuthInputPacket::mYHeadRot</td></tr></tbody></table></td></tr>
<tr><td>Position Mode</td><td>byte</td></tr>
<tr><td>On Ground</td><td><table><tbody><tr><td>bool</td><td>For client bound packets this should have little meaning as it will be reset by the client every frame. For server bound it is true if the player is currently touching the ground. This is indicated by physics trying to move the player down and being stopped by collision. If the player falls freely or moves up it is cleared. If the player isn't affected by gravity this will stay at whatever value it had. The server authoritative near-equivalent of this is PlayerAuthInputPacket::InputData::VerticalCollision</td></tr></tbody></table></td></tr>
<tr><td>Riding Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Dependency on 'Position Mode == Teleport'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Teleportation Cause</td><td>int</td></tr>
  <tr><td>Source Actor Type</td><td>int</td></tr>
  </tbody></table></td></tr>
<tr><td>Tick</td><td><a href="../types/PlayerInputTick.md">PlayerInputTick</a></td></tr>
</tbody></table>