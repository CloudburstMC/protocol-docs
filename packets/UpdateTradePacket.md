# UpdateTradePacket

__ID: 80__

This is used when the player trades with an npc. This sends all of the updated trade info in one big ol' packet.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Container Id</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/ContainerID.md">ContainerID</a></td></tr></tbody></table></td></tr>
<tr><td>Container Type</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/ContainerType.md">ContainerType</a></td></tr></tbody></table></td></tr>
<tr><td>Size</td><td>varint</td></tr>
<tr><td>Trade Tier</td><td>varint</td></tr>
<tr><td>Target Actor ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Last Trading Player ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Display Name</td><td>string</td></tr>
<tr><td>Use New Trade UI</td><td>bool</td></tr>
<tr><td>Using Economy Trade</td><td>bool</td></tr>
<tr><td>Data Tags</td><td><a href="../types/CompoundTag.md">CompoundTag</a></td></tr>
</tbody></table>