# PlayerUpdateEntityOverridesPacket

**ID: 325**  
**Purpose: Updates client entity property override data**  

This will set/remove an override for the indicated property for a specific entity on a client or clear all overrides for that entity. Does not affect server property values.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Property Index</td><td>unsigned varint</td></tr>
<tr><td>Update Type</td><td>byte</td></tr>
<tr><td>Dependency on 'Value Type'</td><td><b>Set Int Override</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Int Value</td><td>int</td></tr>
  </tbody></table><hr>
  <b>Set Float Override</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Float Value</td><td>float</td></tr>
  </tbody></table></td></tr>
</tbody></table>