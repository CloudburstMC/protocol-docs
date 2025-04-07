# PlayerInputPacket

__ID: 57__

Sent only to the server when using legacy client authoritative movement, see ServerAuthMovementMode documentation. This is sent every tick along with MovePlayerPacket when the client is in control of a vehicle.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Move</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
<tr><td>Jumping</td><td><table><tbody><tr><td>bool</td><td>True if the player is holding down the jump input or is auto-jumping.
  In server authoritative movement this is equivalent to `PlayerAuthInputPacket::InputData::Jumping` bit.</td></tr></tbody></table></td></tr>
<tr><td>Sneaking</td><td><table><tbody><tr><td>bool</td><td>This is either the predicted sneak state as determined by sneak input or the latest value received from `SetActorDataPacket` depending on timing.
  In server authoritative movement the closest equivalent is `PlayerAuthInputPacket::InputData::Sneaking` and does not have the timing issue.</td></tr></tbody></table></td></tr>
</tbody></table>