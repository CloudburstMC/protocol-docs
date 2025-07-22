# UpdatePlayerGameTypePacket

**ID: 151**  
**Purpose: Update Player Game Type**  

The server will send this back to all clients on receipt of the SetPlayerGameTypePacket so that cached game type and permissions flags in mLevel on all clients is kept up to date.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Player Game Type</td><td>enum GameType</td></tr>
<tr><td>Target player</td><td>Actor Unique ID</td></tr>
<tr><td>Tick</td><td><table><tbody><tr><td>Input tick</td><td>Most relevant to supply for transitioning into and out of spectator while in motion</td></tr></tbody></table></td></tr>
</tbody></table>