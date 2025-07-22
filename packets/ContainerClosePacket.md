# ContainerClosePacket

**ID: 47**  
**Purpose: After the game deletes the container manager on the client, the client sends this packet. Then the server deletes its container manager, and sends a packet back to the client that closes the container screen.**  

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Container Id</td><td>unsigned byte</td></tr>
<tr><td>Container Type</td><td>unsigned byte</td></tr>
<tr><td>Server Initiated Close</td><td><table><tbody><tr><td>bool</td><td>True if the server initiated the closing</td></tr></tbody></table></td></tr>
</tbody></table>