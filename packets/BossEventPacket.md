# BossEventPacket

**ID: 74**  
**Purpose: Boss Event**  

Two-way packet.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Actor ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Event Type</td><td>unsigned varint</td></tr>
<tr><td>Dependency on 'Event Type'</td><td><b>Add</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Name</td><td><table><tbody><tr><td>string</td><td>Name of the boss to add</td></tr></tbody></table></td></tr>
  <tr><td>FilteredName</td><td><table><tbody><tr><td>string</td><td>Filtered name of the boss to add</td></tr></tbody></table></td></tr>
  <tr><td>Health Percent</td><td><table><tbody><tr><td>float</td><td>Health value of the boss</td></tr></tbody></table></td></tr>
  <tr><td>Darken Screen</td><td><table><tbody><tr><td>unsigned short</td><td>A boolean value for whether or not we should darken the screen (has a 0 or 1 value)</td></tr></tbody></table></td></tr>
  <tr><td>Color</td><td>unsigned varint</td></tr>
  <tr><td>Overlay</td><td>unsigned varint</td></tr>
  </tbody></table><hr>
  <b>Player Added</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
  </tbody></table><hr>
  <b>Player Removed</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
  </tbody></table><hr>
  <b>Update Percent</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Health Percent</td><td>float</td></tr>
  </tbody></table><hr>
  <b>Update Name</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Name</td><td>string</td></tr>
  <tr><td>FilteredName</td><td>string</td></tr>
  </tbody></table><hr>
  <b>Update Properties</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Darken Screen</td><td>unsigned short</td></tr>
  <tr><td>Color</td><td>unsigned varint</td></tr>
  <tr><td>Overlay</td><td>unsigned varint</td></tr>
  </tbody></table><hr>
  <b>Update Style</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Color</td><td>unsigned varint</td></tr>
  <tr><td>Overlay</td><td>unsigned varint</td></tr>
  </tbody></table><hr>
  <b>Query</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>