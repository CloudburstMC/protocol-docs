# TextPacket

__ID: 9__

Used for commands, messages, and other info printed to the screen. Most of which are server->client or server broadcasted to all clients,

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Message Type</td><td>byte</td></tr>
<tr><td>Localize?</td><td>bool</td></tr>
<tr><td>Dependency on 'Message Type'</td><td><b>if (0)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player Name</td><td>string</td></tr>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (2)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  <tr><td>Parameter List</td><td><b>Array Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Parameter</td><td>string</td></tr>
    </tbody></table></td></tr>
  </tbody></table><hr>
  <b>if (3)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  <tr><td>Parameter List</td><td><b>Array Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Parameter</td><td>string</td></tr>
    </tbody></table></td></tr>
  </tbody></table><hr>
  <b>if (4)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  <tr><td>Parameter List</td><td><b>Array Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Parameter</td><td>string</td></tr>
    </tbody></table></td></tr>
  </tbody></table><hr>
  <b>if (5)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (6)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (7)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player Name</td><td>string</td></tr>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (8)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player Name</td><td>string</td></tr>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (9)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (10)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (11)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table></td></tr>
<tr><td>Sender's XUID</td><td>string</td></tr>
<tr><td>Platform Id</td><td>string</td></tr>
<tr><td>Filtered Message</td><td>string</td></tr>
</tbody></table>