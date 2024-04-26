# InventorySlotPacket

__ID: 50__

Updates one slot in an inventory rather than the whole thing. So like animal inventory (horses, donkeys, etc) and chests.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Container ID</td><td>unsigned varint</td></tr>
<tr><td>Slot</td><td>unsigned varint</td></tr>
<tr><td>Item</td><td><a href="../types/NetworkItemStackDescriptor.md">NetworkItemStackDescriptor</a></td></tr>
</tbody></table>