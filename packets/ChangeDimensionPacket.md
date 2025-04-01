# ChangeDimensionPacket

__ID: 61__

The server sends this packet from the level to kick off dimension changing process.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Dimension ID</td><td>varint</td></tr>
<tr><td>Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Respawn</td><td>bool</td></tr>
<tr><td>Loading Screen Id</td><td><a href="../types/Optional_unsigned int.md">std::optional&lt;unsigned int&gt;</a></td></tr>
</tbody></table>