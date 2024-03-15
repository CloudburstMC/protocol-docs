# NetworkChunkPublisherUpdatePacket

__ID: 121__

Tells clients to update the chunk view for the local player.Used (from the server) when a user's Chunk View moves, I.e. the area that determines what chunks exist

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>New position for view</td><td><a href="../types/BlockPos.md">BlockPos</a></td></tr>
<tr><td>New radius for view</td><td>unsigned varint</td></tr>
<tr><td>Server Built Chunks Size</td><td>unsigned int</td></tr>
<tr><td>Server Built Chunks List</td><td><b>Array Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Chunk Pos</td><td><a href="../types/ChunkPos.md">ChunkPos</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>