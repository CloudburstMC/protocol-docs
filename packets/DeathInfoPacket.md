# DeathInfoPacket

__ID: 189__

Sent from the server to client when player dies (Level::onPlayerDeath).

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Death Cause Attack Name</td><td>string</td></tr>
<tr><td>Death Cause Message List</td><td><b>Array Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Death Cause Entity Name</td><td>string</td></tr>
  <tr><td>Death Cause Entity Name</td><td>string</td></tr>
  </tbody></table></td></tr>
</tbody></table>