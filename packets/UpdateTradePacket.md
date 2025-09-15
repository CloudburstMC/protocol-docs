# UpdateTradePacket

**ID: 80**  
**Purpose: This is used when the player trades with an npc. This sends all of the updated trade info in one big ol' packet.**  

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Container Id</td><td>unsigned byte</td></tr>
<tr><td>Type</td><td>unsigned byte</td></tr>
<tr><td>Size</td><td>varint</td></tr>
<tr><td>Trader Tier</td><td>varint</td></tr>
<tr><td>Entity Unique Id</td><td>Actor Unique ID</td></tr>
<tr><td>Last Trading Player</td><td>Actor Unique ID</td></tr>
<tr><td>Display Name</td><td>string</td></tr>
<tr><td>Use New Trade Screen</td><td>bool</td></tr>
<tr><td>Using Economy Trade</td><td>bool</td></tr>
<tr><td>Data</td><td></td></tr>
</tbody></table>