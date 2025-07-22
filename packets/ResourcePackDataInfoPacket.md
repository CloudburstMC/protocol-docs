# ResourcePackDataInfoPacket

**ID: 82**  
**Purpose: Resource Pack Data Info**  

Sent from the serverFileChunkUploader during the initialization of the file uploader. This packet is sent to the primary client.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Resource Name</td><td>string</td></tr>
<tr><td>Chunk Size</td><td>unsigned int</td></tr>
<tr><td>Number of Chunks</td><td>unsigned int</td></tr>
<tr><td>File Size</td><td>unsigned int64</td></tr>
<tr><td>File Hash</td><td>string</td></tr>
<tr><td>Is Premium Pack</td><td><table><tbody><tr><td>bool</td><td>Do you need an entitlement to use this pack?</td></tr></tbody></table></td></tr>
<tr><td>Pack Type</td><td>byte</td></tr>
</tbody></table>