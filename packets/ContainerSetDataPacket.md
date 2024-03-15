# ContainerSetDataPacket

__ID: 51__

This is sent from the server basically any time that the "cooking" state of the brewing stand or the furnace changes (i.e. the loading bar)

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Container ID</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/ContainerID.md">ContainerID</a></td></tr></tbody></table></td></tr>
<tr><td>ID</td><td>varint</td></tr>
<tr><td>Value</td><td>varint</td></tr>
</tbody></table>