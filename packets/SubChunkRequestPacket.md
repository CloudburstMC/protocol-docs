# SubChunkRequestPacket

**ID: 175**  
**Purpose: SubChunkRequestPacket**  

Sent from the client to the server representing a batch of subchunks that the client requests from the server

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Dimension Type</td><td>varint</td></tr>
<tr><td>Center Pos</td><td><a href="../types/SubChunkPos.md">SubChunkPos</a></td></tr>
<tr><td>SubChunk Pos Offset List</td><td><b>Request Count:</b> unsigned int
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>SubChunk Offset Pos</td><td><a href="../types/SubChunkPacket_SubChunkPosOffset.md">SubChunkPacket::SubChunkPosOffset</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>