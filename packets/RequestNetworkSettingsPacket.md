# RequestNetworkSettingsPacket

**ID: 193**  
**Purpose: Requests tunable options from host to client (compression threshold and algorithm).**  

This is the initial packet sent from the client to initiate a connection. NOTE: this packet should not contain anything other than the client version, don't add new data here.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>ClientNetworkVersion</td><td>int</td></tr>
</tbody></table>