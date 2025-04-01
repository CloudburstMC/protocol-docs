# ItemInstanceUserData

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>User Data Serialization Marker</td><td><table><tbody><tr><td>short</td><td>(-1) marking start of data</td></tr></tbody></table></td></tr>
<tr><td>User Data Serialization Version</td><td><table><tbody><tr><td>byte</td><td>Currently 1</td></tr></tbody></table></td></tr>
<tr><td>User Data Tag(s)</td><td><a href="../types/CompoundTag.md">CompoundTag</a></td></tr>
<tr><td>Can Place On Blocks</td><td><b>List Size:</b> unsigned varint
  Blocks that this item can be placed on.  
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Block Raw Name ID</td><td>string</td></tr>
  </tbody></table></td></tr>
<tr><td>Can Destroy Blocks</td><td><b>List Size:</b> unsigned varint
  Blocks that this item can destroy.  
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Block Raw Name ID</td><td>string</td></tr>
  </tbody></table></td></tr>
</tbody></table>