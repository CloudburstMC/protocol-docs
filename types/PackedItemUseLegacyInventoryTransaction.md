# PackedItemUseLegacyInventoryTransaction

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>ID</td><td><a href="../types/TypedClientNetId_ItemStackLegacyRequestIdTag.md">TypedClientNetId&lt;struct ItemStackLegacyRequestIdTag,int,0&gt;</a></td></tr>
<tr><td>Dependency on 'ID is valid?'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Container Slots</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Container Enum Name</td><td>byte</td></tr>
    <tr><td>Slots</td><td><b>List Size:</b> unsigned varint
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Slot</td><td>byte</td></tr>
      </tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>mTransaction->mTransaction</td><td><a href="../types/InventoryTransaction.md">InventoryTransaction</a></td></tr>
<tr><td>Action Type</td><td>unsigned varint</td></tr>
<tr><td>Trigger Type</td><td><table><tbody><tr><td>unsigned varint</td><td>PlayerInput if it's a direct result from a player's initial button input,		SimulationTick if the player is holding down the input button started from a previous tick.</td></tr></tbody></table></td></tr>
<tr><td>Position</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
<tr><td>Face</td><td>varint</td></tr>
<tr><td>Slot</td><td>varint</td></tr>
<tr><td>Item</td><td><a href="../types/NetworkItemStackDescriptor.md">NetworkItemStackDescriptor</a></td></tr>
<tr><td>From Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Click Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Target Block Id</td><td>unsigned varint</td></tr>
<tr><td>Client Interact Prediction</td><td>byte</td></tr>
</tbody></table>