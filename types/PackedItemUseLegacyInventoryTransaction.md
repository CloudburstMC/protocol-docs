# PackedItemUseLegacyInventoryTransaction

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>ID</td><td><a href="../types/TypedClientNetId_ItemStackLegacyRequestIdTag.md">TypedClientNetId<struct ItemStackLegacyRequestIdTag,int,0></a></td></tr>
<tr><td>Dependency on 'valid ID'</td><td><b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Container Slots</td><td><b>Array Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Container Enum Name</td><td>byte</td></tr>
    <tr><td>Slots</td><td><b>Array Size:</b> unsigned varint
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Slot</td><td>byte</td></tr>
      </tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Actions</td><td><b>Array Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Action</td><td><a href="../types/InventoryAction.md">InventoryAction</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Action Type</td><td>unsigned varint</td></tr>
<tr><td>Position</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
<tr><td>Face</td><td>varint</td></tr>
<tr><td>Slot</td><td>varint</td></tr>
<tr><td>Item</td><td><a href="../types/NetworkItemStackDescriptor.md">NetworkItemStackDescriptor</a></td></tr>
<tr><td>From Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Click Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Target Block Id</td><td>unsigned varint</td></tr>
</tbody></table>