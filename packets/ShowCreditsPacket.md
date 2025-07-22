# ShowCreditsPacket

**ID: 75**  
**Purpose: Starts on server when the credits screen should pop up.**  

That packet is sent to the client. When the credits have concluded, a packet is sent back to the server to let it know to reinstate the player watching the credits.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Player Runtime ID</td><td>Actor Runtime ID</td></tr>
<tr><td>Credits State</td><td>varint</td></tr>
</tbody></table>