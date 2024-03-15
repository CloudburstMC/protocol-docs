# BossEventPacket

__ID: 74__

Two-way packet.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Actor ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Event Type</td><td><table><tbody><tr><td>int</td><td><a href="../enums/BossEventUpdateType.md">BossEventUpdateType</a></td></tr></tbody></table></td></tr>
<tr><td>Dependency on 'Event Type'</td><td><b>if (0)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Name</td><td><table><tbody><tr><td>string</td><td>Name of the boss to add</td></tr></tbody></table></td></tr>
  <tr><td>Health Percent</td><td><table><tbody><tr><td>float</td><td>Health value of the boss</td></tr></tbody></table></td></tr>
  <tr><td>Darken Screen</td><td><table><tbody><tr><td>unsigned short</td><td>A boolean value for whether or not we should darken the screen (has a 0 or 1 value)</td></tr></tbody></table></td></tr>
  <tr><td>Color</td><td>unsigned varint</td></tr>
  <tr><td>Overlay</td><td>unsigned varint</td></tr>
  </tbody></table><hr>
  <b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
  </tbody></table><hr>
  <b>if (3)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
  </tbody></table><hr>
  <b>if (4)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Health Percent</td><td>float</td></tr>
  </tbody></table><hr>
  <b>if (5)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Name</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (6)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Darken Screen</td><td>unsigned short</td></tr>
  <tr><td>Color</td><td>unsigned varint</td></tr>
  <tr><td>Overlay</td><td>unsigned varint</td></tr>
  </tbody></table><hr>
  <b>if (7)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Color</td><td>unsigned varint</td></tr>
  <tr><td>Overlay</td><td>unsigned varint</td></tr>
  </tbody></table><hr>
  <b>if (8)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>