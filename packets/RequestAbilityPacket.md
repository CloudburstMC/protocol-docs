# RequestAbilityPacket

__ID: 184__

Sent from client to server. Used to request an ability change.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Ability</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/AbilitiesIndex.md">AbilitiesIndex</a></td></tr></tbody></table></td></tr>
<tr><td>Value Type</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/RequestAbilityPacket_Type.md">RequestAbilityPacket::Type</a></td></tr></tbody></table></td></tr>
<tr><td>Dependency on 'Value Type'</td><td><b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Varible Value</td><td>bool</td></tr>
  <tr><td>Default Value = 0.0</td><td>float</td></tr>
  </tbody></table><hr>
  <b>if (2)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Default Value = false</td><td>bool</td></tr>
  <tr><td>Varible Value</td><td>float</td></tr>
  </tbody></table></td></tr>
</tbody></table>