# SetPlayerGameTypePacket

**ID: 62**  
**Purpose: Set Player Game Type**  

The client handles the change of the UI element (the gametype dropdown, although this can be avoided by changing via command or on the server), then the client sends a packet to the server, then the server changes the player's gametype and sends a packet back (UpdatePlayerGameTypePacket) to make sure it matches on the client.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Player Game Type</td><td>enum GameType</td></tr>
</tbody></table>