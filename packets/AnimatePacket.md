# AnimatePacket

__ID: 44__

Combination of server bound and client bound packets to trigger animations. In legacy client authoritative movement this is where boat paddle inputs arrive. See Player Auth Input for documentation on how to compute equivalents to Action::RowRight and Action::RowLeft

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Action</td><td>varint</td></tr>
<tr><td>Target Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Dependency on 'Action'</td><td><b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Rowing Time</td><td><table><tbody><tr><td>float</td><td>Only written for rowing actions</td></tr></tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>