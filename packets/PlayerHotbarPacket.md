# PlayerHotbarPacket

__ID: 48__

Sent from the server when the player uses pick block on actors or blocks, in addition to the player uses the clear, give,

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Selected Slot</td><td>unsigned varint</td></tr>
<tr><td>Container ID</td><td>byte</td></tr>
<tr><td>Should select slot?</td><td>bool</td></tr>
</tbody></table>