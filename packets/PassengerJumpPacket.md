# PassengerJumpPacket

__ID: 20__

Legacy client authoritative movement only. Sent for jumping in horses when releasing the spacebar. Specifically if the entity has `ActorFlags::CAN_POWER_JUMP`, `ActorFlags::WASD_CONTROLLED` and the `minecraft:horse.jump_strength` attribute. In server authoritative movement this is not explicitly specified but can be simulated using information from Player Auth Input, see that packet for more details.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Jump Scale</td><td>varint</td></tr>
</tbody></table>