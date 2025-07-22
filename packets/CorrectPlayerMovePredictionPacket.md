# CorrectPlayerMovePredictionPacket

**ID: 161**  
**Purpose: Sent to a player when their simulation of movement mismatches enough from the server that it wants to correct the client.**  

Used only in server authoritative movement mode, see ServerAuthMovementMode documentation. Since it is sent to the specified client the target player is implied to be the receiver. It is an optional part of the server authoritative protocol. A server could choose to never send this or do all corrections through MovePlayerPacket, although doing so would likely provide less smooth results.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>PredictionType</td><td><table><tbody><tr><td>enum enum RewindType</td><td>Vehicle or Player Prediction</td></tr></tbody></table></td></tr>
<tr><td>Pos</td><td><table><tbody><tr><td>X</td><td>Corrected position</td></tr></tbody></table></td></tr>
<tr><td>Pos Delta</td><td><table><tbody><tr><td>X</td><td>Corrected velocity</td></tr></tbody></table></td></tr>
<tr><td>Rotation</td><td><table><tbody><tr><td>X</td><td>Corrected rotation. Only sent when PredictionType is Vehicle</td></tr></tbody></table></td></tr>
<tr><td>VehicleAngularVelocity</td><td><table><tbody><tr><td>float</td><td>Angular Velocity for a vehicle. Only sent when PredictionType is Vehicle</td></tr></tbody></table></td></tr>
<tr><td>On Ground</td><td><table><tbody><tr><td>bool</td><td>Is on ground</td></tr></tbody></table></td></tr>
<tr><td>Tick</td><td><table><tbody><tr><td>Input tick</td><td>Which frame we're correcting; should match the tick in the Player Auth Input packet</td></tr></tbody></table></td></tr>
</tbody></table>