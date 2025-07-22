# StructureTemplateDataResponsePacket

**ID: 133**  
**Purpose: Structure Data Response**  

Used to reply to a request for structure information.This is used in exporting from load, exporting from save, and querying saved structures from structure blocks.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Structure Name</td><td>string</td></tr>
<tr><td>Dependency on 'Requested structure exists?'</td><td><b>If False</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Failure</td><td>bool</td></tr>
  <tr><td>Response Type</td><td>byte</td></tr>
  </tbody></table><hr>
  <b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Success</td><td>bool</td></tr>
  <tr><td>Structure's NBT</td><td><a href="../types/CompoundTag.md">CompoundTag</a></td></tr>
  <tr><td>Response Type</td><td>byte</td></tr>
  </tbody></table></td></tr>
</tbody></table>