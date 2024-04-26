# CorrectPlayerMovePredictionPacket

__ID: 161__

Sent to a player when their simulation of movement mismatches enough from the server that it wants to correct the client.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>PredictionType</td><td><table><tbody><tr><td>byte</td><td>Vehicle or Player Prediction</td></tr></tbody></table></td></tr>
<tr><td>Pos</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Pos Delta</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>On Ground</td><td><table><tbody><tr><td>bool</td><td>Is on ground</td></tr></tbody></table></td></tr>
<tr><td>Tick</td><td><table><tbody><tr><td>unsigned varint64</td><td>Which frame we're correcting; should match the tick in the Player Auth Input packet</td></tr></tbody></table></td></tr>
</tbody></table>