# MapInfoRequestPacket

**ID: 68**  
**Purpose: In the case of the client being unable to find map data for a map item it sends a uuid for a map to the server.**  

If the server finds the map, it sends the data back. If it can't find the map, it creates it and sends the map and data back. (the map creation data packet and the map data packet are separate packets). The response from the server potentially has to load from disk, just an fyi. This packet is fired via map item tick, if the map data we have is invalid, or if the map is placed in an item frame. For Client Side Generation when we re-sample pixels from the Client's ChunkSource we need to inform the Server's map about these new pixels so that it can save them to LevelStorage. Use this packet to send to the Server the extra pixels

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Map Unique ID</td><td>Actor Unique ID</td></tr>
<tr><td>Client Pixels List</td><td><table><tbody><tr><td>List Size</td><td>These are sent from the client to tell the Server map about terrain pixels it doesn't know about</td></tr></tbody></table></td></tr>
</tbody></table>