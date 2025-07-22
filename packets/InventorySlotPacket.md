# InventorySlotPacket

**ID: 50**  
**Purpose: Inventory Slot**  

Updates one slot in an inventory rather than the whole thing. So like animal inventory (horses, donkeys, etc) and chests.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Container ID</td><td>unsigned varint</td></tr>
<tr><td>Slot</td><td>unsigned varint</td></tr>
<tr><td>Full Container Name</td><td><a href="../types/FullContainerName.md">FullContainerName</a></td></tr>
<tr><td>Storage Item</td><td><a href="../types/NetworkItemStackDescriptor.md">NetworkItemStackDescriptor</a></td></tr>
<tr><td>Item</td><td><a href="../types/NetworkItemStackDescriptor.md">NetworkItemStackDescriptor</a></td></tr>
</tbody></table>