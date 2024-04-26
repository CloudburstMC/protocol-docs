# ContainerClosePacket

__ID: 47__

After the game deletes the container manager on the client, the client sends this packet.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Container ID</td><td>byte</td></tr>
<tr><td>Server Initiated Close</td><td><table><tbody><tr><td>bool</td><td>True if the server initiated the closing</td></tr></tbody></table></td></tr>
</tbody></table>