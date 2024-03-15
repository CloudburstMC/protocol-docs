# SetScorePacket

__ID: 108__

This packet is used to set the scoreboard which is used for 3rd party content.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Score Packet Type</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/ScorePacketType.md">ScorePacketType</a></td></tr></tbody></table></td></tr>
<tr><td>Score Packet Info</td><td><b>Array Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Id</td><td><a href="../types/ScoreboardId.md">ScoreboardId</a></td></tr>
  <tr><td>Objective Name</td><td>string</td></tr>
  <tr><td>Score Value</td><td>int</td></tr>
  <tr><td>Dependency on 'Is Change Type'</td><td><b>if (1)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Dependency on 'Identity Definition Type'</td><td><b>if (1)</b><br>
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Identity Definition Type</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/IdentityDefinition_Type.md">IdentityDefinition::Type</a></td></tr></tbody></table></td></tr>
      <tr><td>Player Unique Id</td><td>varint64</td></tr>
      </tbody></table><hr>
      <b>if (2)</b><br>
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Identity Definition Type</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/IdentityDefinition_Type.md">IdentityDefinition::Type</a></td></tr></tbody></table></td></tr>
      <tr><td>Actor Id</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
      </tbody></table><hr>
      <b>if (3)</b><br>
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Identity Definition Type</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/IdentityDefinition_Type.md">IdentityDefinition::Type</a></td></tr></tbody></table></td></tr>
      <tr><td>Fake Player Name</td><td>string</td></tr>
      </tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>