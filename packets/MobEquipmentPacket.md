# MobEquipmentPacket

**ID: 31**  
**Purpose: Mob Equipment**  

A bunch of things use this both server to client and can still be sent from the client if LocalPlayer's inventory doesn't match the inventory sent (deprecated pattern).

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Item</td><td><a href="../types/NetworkItemStackDescriptor.md">NetworkItemStackDescriptor</a></td></tr>
<tr><td>Slot</td><td>byte</td></tr>
<tr><td>Selected Slot</td><td>byte</td></tr>
<tr><td>Container ID</td><td>byte</td></tr>
</tbody></table>