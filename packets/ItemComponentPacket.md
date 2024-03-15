# ItemComponentPacket

__ID: 162__

Definitions for component items. Should be fine to send one with an empty mItems array after the StartGamePacket.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Items</td><td><b>Array Size:</b> unsigned varint
  Array of component based items  
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>ComponentItem name</td><td>string</td></tr>
  <tr><td>Component data</td><td><a href="../types/CompoundTag.md">CompoundTag</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>