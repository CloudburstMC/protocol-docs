# GameRulesChangedPacketData

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Rules List</td><td><b>Array Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Rule Name</td><td>string</td></tr>
  <tr><td>Can Be Modified By Player</td><td>bool</td></tr>
  <tr><td>Rule Type</td><td><table><tbody><tr><td>unsigned varint</td><td><a href="../enums/GameRule_Type.md">GameRule::Type</a></td></tr></tbody></table></td></tr>
  <tr><td>Dependency on 'Rule Type'</td><td><b>if (1)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Rule Value</td><td>bool</td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>