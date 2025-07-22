# ClientboundDebugRendererPacket

**ID: 164**  
**Purpose: ClientboundDebugRendererPacket**  

Sent from the server to client to add/remove debug rendering objects

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Debug Marker Type</td><td>unsigned int</td></tr>
<tr><td>Dependency on 'Debug Marker Type'</td><td><b>AddDebugMarkerCube</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Debug Marker Text</td><td>string</td></tr>
  <tr><td>Debug Marker Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
  <tr><td>Debug Marker Color red</td><td>float</td></tr>
  <tr><td>Debug Marker Color green</td><td>float</td></tr>
  <tr><td>Debug Marker Color blue</td><td>float</td></tr>
  <tr><td>Debug Marker Color alpha</td><td>float</td></tr>
  <tr><td>Debug Marker Duration Milliseconds</td><td>unsigned int64</td></tr>
  </tbody></table></td></tr>
</tbody></table>