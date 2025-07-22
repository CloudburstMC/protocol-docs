# SetTimePacket

**ID: 10**  
**Purpose: Set Time**  

Every so often (and at login) the server sends the current time to the client, and additionally the client can set the server time through 2 commands: DayLockCommand and TimeCommand

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Time</td><td>varint</td></tr>
</tbody></table>