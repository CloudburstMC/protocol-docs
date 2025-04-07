# CreativeContentPacket

__ID: 145__

Sent once by the server on startup to tell clients all of the items that can show up in the creative menu, blocks and items.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Write Entries</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Creative Net Id</td><td><a href="../types/TypedServerNetId_CreativeItemNetIdTag.md">TypedServerNetId&lt;struct CreativeItemNetIdTag,unsigned int,0&gt;</a></td></tr>
  <tr><td>Item Instance</td><td><a href="../types/NetworkItemInstanceDescriptor.md">NetworkItemInstanceDescriptor</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>