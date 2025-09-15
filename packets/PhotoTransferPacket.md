# PhotoTransferPacket

**ID: 99**  
**Purpose: There is a camera item in EDU and they can use it to take screenshots and add them to a scrapbook.**  

When the player uses the camera item or adds a photo to the scrapbook it sends the photo to the server, then the server sends a response back on whether that was successful or not. Either uploads a photo to the server's photoStorage or request one from it to be stored in client's photoStorage. If no mPhotoData is provided it is a request for the given filename.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Photo Name</td><td>string</td></tr>
<tr><td>Photo Data</td><td>string</td></tr>
<tr><td>Book ID</td><td>string</td></tr>
<tr><td>Type</td><td>enum PhotoType</td></tr>
<tr><td>Source Type</td><td>enum PhotoType</td></tr>
<tr><td>Owner ID</td><td>int64</td></tr>
<tr><td>New Photo Name</td><td>string</td></tr>
</tbody></table>