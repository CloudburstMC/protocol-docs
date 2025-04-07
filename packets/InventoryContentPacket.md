# InventoryContentPacket

__ID: 49__

This is used for updating an entire container. Example uses include: player respawned, replace items command, 3rd party content calls sendInventory(), block picking.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Inventory Id</td><td>unsigned varint</td></tr>
<tr><td>Slots</td><td><b>Array Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Item stack</td><td><a href="../types/NetworkItemStackDescriptor.md">NetworkItemStackDescriptor</a></td></tr>
  </tbody></table></td></tr>
<tr><td>ID of the particular container instance if this is a dynamic container, otherwise zero</td><td>unsigned varint</td></tr>
</tbody></table>