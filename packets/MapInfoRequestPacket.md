# MapInfoRequestPacket

**ID: 68**  
**Purpose: MapInfoRequestPacket**  

In the case of the client being unable to find map data for a map item it sends a uuid for a map to the server.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Map Unique ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Client Pixels List Size</td><td>unsigned int</td></tr>
<tr><td>Dependency on 'Client Pixels List Size > 0 ?'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Client Pixels List</td><td>These are sent from the client to tell the Server map about terrain pixels it doesn't know about  
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>pixel</td><td>unsigned int</td></tr>
    <tr><td>index</td><td>unsigned short</td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>