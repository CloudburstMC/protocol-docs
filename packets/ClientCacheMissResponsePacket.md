# ClientCacheMissResponsePacket

**ID: 136**  
**Purpose: Client Cache Miss Response Packet**  

Any missing blob should just be thrown into one of these packet ASAP and sent.Only active in a *real* client-server scenario. This packet is just a list of pairs sent from server to client.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Missing Blobs</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Blob Id</td><td>unsigned int64</td></tr>
  <tr><td>Blob Data</td><td><table><tbody><tr><td>string</td><td>Subchunk data (see https://gist.github.com/Tomcc/a96af509e275b1af483b25c543cfbf37) plus biome data</td></tr></tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>