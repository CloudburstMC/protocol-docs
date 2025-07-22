# NetworkChunkPublisherUpdatePacket

**ID: 121**  
**Purpose: Tells clients to update the chunk view for the local player.**  

Used (from the server) when a user's Chunk View moves, I.e. the area that determines what chunks exist. For ClientSideGeneration we also send the client a list of ChunkPos that the Server will fully build.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>New position for view</td><td>X</td></tr>
<tr><td>New radius for view</td><td>unsigned varint</td></tr>
<tr><td>Server Built Chunks List</td><td>List Size</td></tr>
</tbody></table>