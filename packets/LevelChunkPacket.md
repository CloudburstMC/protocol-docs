# LevelChunkPacket

**ID: 58**  
**Purpose: Level Chunk Packet**  

Used to start a chunk transaction.Used to start a Chunk Transaction - sends a list of hashes for the chunks it needs to send, followed by border blocks, block entities, and biomes.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Chunk Position</td><td><a href="../types/ChunkPos.md">ChunkPos</a></td></tr>
<tr><td>Dimension Id</td><td>varint</td></tr>
<tr><td>Dependency on 'Client Needs To Request Subchunks?'</td><td><b>If False</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Sub-chunks Count</td><td>unsigned varint</td></tr>
  </tbody></table><hr>
  <b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Dependency on 'Client Request SubChunk Limit < 0?'</td><td><b>If False</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Partial SubChunk Count When Client Requesting</td><td><table><tbody><tr><td>unsigned varint</td><td>Currently max unsigned 32-bit int</td></tr></tbody></table></td></tr>
    <tr><td>Client Request SubChunk Limit</td><td>unsigned short</td></tr>
    </tbody></table><hr>
    <b>If True</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>SubChunk Count When Client Requesting</td><td><table><tbody><tr><td>unsigned varint</td><td>Currently max unsigned 32-bit int</td></tr></tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Cache Enabled</td><td><table><tbody><tr><td>bool</td><td>Lets the server turn off the cache for this chunk even if the Client signaled it supports it.</td></tr></tbody></table></td></tr>
<tr><td>Dependency on 'Cache Enabled?'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Cache Blobs</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Blob Id</td><td>unsigned int64</td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Serialized Chunk Data</td><td><table><tbody><tr><td>string</td><td>See https://gist.github.com/Tomcc/a96af509e275b1af483b25c543cfbf37</td></tr></tbody></table></td></tr>
</tbody></table>