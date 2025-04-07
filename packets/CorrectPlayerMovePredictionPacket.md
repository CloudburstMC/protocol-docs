# CorrectPlayerMovePredictionPacket

__ID: 161__

Used only in server authoritative movement mode, see ServerAuthMovementMode documentation. Sent to a player when their simulation of movement mismatches enough from the server that it wants to correct the client. Since it is sent to the specified client the target player is implied to be the receiver. It is an optional part of the server authoritative protocol. A server could choose to never send this or do all corrections through MovePlayerPacket, although doing so would likely provide less smooth results.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>PredictionType</td><td><table><tbody><tr><td>byte</td><td>Vehicle or Player Prediction</td></tr></tbody></table></td></tr>
<tr><td>Pos</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Pos Delta</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>On Ground</td><td><table><tbody><tr><td>bool</td><td>Is on ground</td></tr></tbody></table></td></tr>
<tr><td>Tick</td><td><a href="../types/PlayerInputTick.md">PlayerInputTick</a></td></tr>
</tbody></table>