# SetActorMotionPacket

**ID: 40**  
**Purpose: This is used for the server to set the velocity of a client actor.**  

It is primarily relevant for client predicted entities like the player or a boat or horse they are in control of. For most other actor types it does nothing. This is one of the packets that can directly affect player motion, for others, see: - MovePlayerPacket - CorrectPlayerMovePredictionPacket

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Runtime ID</td><td>Actor Runtime ID</td></tr>
<tr><td>Motion</td><td>X</td></tr>
<tr><td>Tick</td><td>Input tick</td></tr>
</tbody></table>