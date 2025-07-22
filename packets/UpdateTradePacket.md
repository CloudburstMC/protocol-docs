# UpdateTradePacket

**ID: 80**  
**Purpose: UpdateTradePacket**  

This is used when the player trades with an npc. This sends all of the updated trade info in one big ol' packet.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Container Id</td><td>byte</td></tr>
<tr><td>Type</td><td>byte</td></tr>
<tr><td>Size</td><td>varint</td></tr>
<tr><td>Trader Tier</td><td>varint</td></tr>
<tr><td>Entity Unique Id</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Last Trading Player</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Display Name</td><td>string</td></tr>
<tr><td>Use New Trade Screen</td><td>bool</td></tr>
<tr><td>Using Economy Trade</td><td>bool</td></tr>
<tr><td>Byte</td><td>byte</td></tr>
<tr><td>String</td><td>string</td></tr>
<tr><td>Byte</td><td>byte</td></tr>
</tbody></table>