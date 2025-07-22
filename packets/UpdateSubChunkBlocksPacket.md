# UpdateSubChunkBlocksPacket

**ID: 172**  
**Purpose: UpdateSubChunkBlocksPacket**  

Packet sent for every set of blocks changed in a sub chunk every tick.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Sub Chunk Block Position</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
<tr><td>Blocks Changed - Standards</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Pos</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
  <tr><td>Runtime Id</td><td>unsigned varint</td></tr>
  <tr><td>Update Flags</td><td>unsigned varint</td></tr>
  <tr><td>Sync Message - Entity Unique ID</td><td>unsigned varint64</td></tr>
  <tr><td>Sync Message - Message</td><td>unsigned varint</td></tr>
  </tbody></table></td></tr>
<tr><td>Blocks Changed - Extras</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Pos</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
  <tr><td>Runtime Id</td><td>unsigned varint</td></tr>
  <tr><td>Update Flags</td><td>unsigned varint</td></tr>
  <tr><td>Sync Message - Entity Unique ID</td><td>unsigned varint64</td></tr>
  <tr><td>Sync Message - Message</td><td>unsigned varint</td></tr>
  </tbody></table></td></tr>
</tbody></table>