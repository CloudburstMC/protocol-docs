# PlayerLocationPacket

**ID: 326**  
**Purpose: PlayerLocationPacket**  

Updates the client with the position of a player in the same dimension outside of simulation distance, or whether to hide a player.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Packet Type</td><td>int</td></tr>
<tr><td>Dependency on 'Server Location Packet Type'</td><td><b>PlayerLocationCoordinates</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Target Actor ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
  <tr><td>Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
  </tbody></table><hr>
  <b>PlayerLocationHide</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Target Actor ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>