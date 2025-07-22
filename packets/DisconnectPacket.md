# DisconnectPacket

**ID: 5**  
**Purpose: Disconnect Player**  

Sent from server. It is not fired if you are in a singleplayer game and you leave, but it is fired when there are split-screen clients.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Reason</td><td>varint</td></tr>
<tr><td>Skip Message</td><td>bool</td></tr>
<tr><td>Dependency on 'Has Message?'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  <tr><td>Filtered Message</td><td>string</td></tr>
  </tbody></table></td></tr>
</tbody></table>