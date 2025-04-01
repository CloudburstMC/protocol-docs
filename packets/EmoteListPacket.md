# EmoteListPacket

__ID: 152__

Allows clients to download emotes that other clients have equipped.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Runtime id</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Emote piece ids</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Piece id</td><td><a href="../types/mce_UUID.md">mce::UUID</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>