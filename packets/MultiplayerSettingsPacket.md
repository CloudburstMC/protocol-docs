# MultiplayerSettingsPacket

**ID: 139**  
**Purpose: Syncs multiplayer settings**  

This is used by EDU for joining players and removing players from your session, the settings (there is only one) is an enum for enabling/disabling/refreshing multiplayer join codes. Starts on the client, and a response to the client is issued from the server.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>PacketType</td><td>enum MultiplayerSettingsPacketType</td></tr>
</tbody></table>