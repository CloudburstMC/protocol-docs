# RequestChunkRadiusPacket

**ID: 69**  
**Purpose: The client can't just change the view radius without the server's approval, otherwise there could be holes on unrendered area.**  

This packet is to make sure that the server expands/shrinks first. Additionally for ClientSide Chunk Generation we can send a byte, based on client's hardware capabilities what is the max chunk radius client can handle.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Chunk Radius</td><td>varint</td></tr>
<tr><td>Max ChunkRadius</td><td>unsigned byte</td></tr>
</tbody></table>