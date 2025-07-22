# SpawnExperienceOrbPacket

**ID: 66**  
**Purpose: Spawn Experience Orb**  

Note: This can be seen as "ContainerWantSetSlotPacket" when sent from client to server. Currently, the client handles side-effects relating to it's own inventory, regardless of the success of the operation.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Position</td><td>X</td></tr>
<tr><td>XP Value</td><td>varint</td></tr>
</tbody></table>