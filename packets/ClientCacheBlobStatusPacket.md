# ClientCacheBlobStatusPacket

__ID: 135__

Sent periodically by the client to update the server on which blob it has (ACK) and which blobs it is lacking (MISS).Indicates status of binary blob transfers from server. Used heavily when server is sending chunks.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Number of missing blobs</td><td>unsigned varint</td></tr>
<tr><td>Number of obtained blobs</td><td>unsigned varint</td></tr>
<tr><td>Missing Blobs</td><td><table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Blob Id</td><td>unsigned int64</td></tr>
  </tbody></table></td></tr>
<tr><td>Obtained Blobs</td><td><table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Blob Id</td><td>unsigned int64</td></tr>
  </tbody></table></td></tr>
</tbody></table>