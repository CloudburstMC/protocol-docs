# TextPacket

**ID: 9**  
**Purpose: Text Message**  

Used for commands, messages, and other info printed to the screen. Most of which are server->client or server broadcasted to all clients,

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Message Type</td><td>byte</td></tr>
<tr><td>Localize?</td><td>bool</td></tr>
<tr><td>Dependency on 'Message Type'</td><td><b>Raw</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>Chat</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player Name</td><td>string</td></tr>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>Translate</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  <tr><td>Parameter List</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Parameter</td><td>string</td></tr>
    </tbody></table></td></tr>
  </tbody></table><hr>
  <b>Popup</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  <tr><td>Parameter List</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Parameter</td><td>string</td></tr>
    </tbody></table></td></tr>
  </tbody></table><hr>
  <b>Jukebox Popup</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  <tr><td>Parameter List</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Parameter</td><td>string</td></tr>
    </tbody></table></td></tr>
  </tbody></table><hr>
  <b>Tip</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>System Message</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>Whisper</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player Name</td><td>string</td></tr>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>Announcement</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player Name</td><td>string</td></tr>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>Text Object Whisper</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>Text Object</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table><hr>
  <b>Text Object Announcement</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Message</td><td>string</td></tr>
  </tbody></table></td></tr>
<tr><td>Sender's XUID</td><td>string</td></tr>
<tr><td>Platform Id</td><td>string</td></tr>
<tr><td>Filtered Message</td><td>string</td></tr>
</tbody></table>