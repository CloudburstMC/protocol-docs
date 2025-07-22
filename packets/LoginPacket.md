# LoginPacket

**ID: 1**  
**Purpose: Login**  

Sent once from client to server at login.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Client Network Version</td><td>big endian int</td></tr>
<tr><td>Connection Request</td><td><table><tbody><tr><td>string</td><td>see @connectionRequest.html#diagram@</td></tr></tbody></table></td></tr>
</tbody></table>