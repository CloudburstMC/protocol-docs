# PlayStatusPacket

**ID: 2**  
**Purpose: Describes the login status of the player**  

Used after the Server handles a Login or (Sub)Client Authentication Packet If everything is good, then it sends this packet to the client to finish the handshake. If everything is not good, it terminates the connection.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Status</td><td>enum PlayStatus</td></tr>
</tbody></table>