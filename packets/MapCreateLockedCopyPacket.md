# MapCreateLockedCopyPacket

**ID: 131**  
**Purpose: This is fired when the user locks a map item utilizing the Cartography Table in game.**  

It sends the original map id and the new map id. On the server it follows a similar process to creating a new map, sends the data and the map info to the client.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Original Map Id</td><td><table><tbody><tr><td>Actor Unique ID</td><td>Id of the map being locked.</td></tr></tbody></table></td></tr>
<tr><td>New Map Id</td><td><table><tbody><tr><td>Actor Unique ID</td><td>Id that the new map should have.</td></tr></tbody></table></td></tr>
</tbody></table>