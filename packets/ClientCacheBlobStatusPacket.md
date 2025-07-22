# ClientCacheBlobStatusPacket

**ID: 135**  
**Purpose: Client Cache Blob Status Packet**  

Sent periodically by the client to update the server on which blob it has (ACK) and which blobs it is lacking (MISS).Indicates status of binary blob transfers from server. Used heavily when server is sending chunks.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Missing Ids Size</td><td>unsigned varint</td></tr>
<tr><td>Found Ids Size</td><td>unsigned varint</td></tr>
<tr><td>Missing Ids</td><td><table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Blob Id</td><td><a href="../types/unsigned int64.md">unsigned int64</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Found Ids</td><td><table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Blob Id</td><td><a href="../types/unsigned int64.md">unsigned int64</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>