# DisconnectPacket

__ID: 5__

Sent from server. It is not fired if you are in a singleplayer game and you leave, but it is fired when there are split-screen clients.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Reason</td><td>varint</td></tr>
<tr><td>Skip Message</td><td>bool</td></tr>
<tr><td>Dependency on 'Skip Message'</td><td><b>if (0)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table></td></tr>
</tbody></table>