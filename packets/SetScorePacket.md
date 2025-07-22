# SetScorePacket

**ID: 108**  
**Purpose: Set Score**  

This packet is used to set the scoreboard which is used for 3rd party content.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Score Packet Type</td><td>byte</td></tr>
<tr><td>Score Info</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Id</td><td><a href="../types/ScoreboardId.md">ScoreboardId</a></td></tr>
  <tr><td>Objective Name</td><td>string</td></tr>
  <tr><td>Score Value</td><td>int</td></tr>
  <tr><td>Dependency on 'Is Change Type'</td><td><b>If True</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Identity Definition Type</td><td>byte</td></tr>
    <tr><td>Dependency on 'Change Type Data'</td><td><b>Identity Definition Type Player</b><br>
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Player Unique Id</td><td>varint64</td></tr>
      </tbody></table><hr>
      <b>Identity Definition Type Entity</b><br>
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Actor Id</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
      </tbody></table><hr>
      <b>Default</b><br>
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Fake Player Name</td><td>string</td></tr>
      </tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>