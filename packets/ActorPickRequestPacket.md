# ActorPickRequestPacket

**ID: 35**  
**Purpose: Player clicks on an actor in the world, eg a chicken.**  

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Actor ID</td><td><table><tbody><tr><td>int64</td><td>Target Actor ID</td></tr></tbody></table></td></tr>
<tr><td>Max Slots</td><td><table><tbody><tr><td>unsigned byte</td><td>number of empty hotbar slots (to decide whether to overwrite a slot or add it to an empty one)</td></tr></tbody></table></td></tr>
<tr><td>With Data</td><td><table><tbody><tr><td>bool</td><td>whether we want to store the NBT data along with the item</td></tr></tbody></table></td></tr>
</tbody></table>