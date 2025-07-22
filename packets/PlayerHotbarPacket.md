# PlayerHotbarPacket

**ID: 48**  
**Purpose: Sent from the server when the player uses pick block on actors or blocks, in addition to the player uses the clear, give, or replace item command or if the serverplayer uses _sendAdditionalLevelData().**  

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Selected Slot</td><td>unsigned varint</td></tr>
<tr><td>Container ID</td><td>unsigned byte</td></tr>
<tr><td>Should select slot?</td><td>bool</td></tr>
</tbody></table>