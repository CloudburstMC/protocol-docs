# PlayerAuthInputPacket

__ID: 144__

Added for Server Authoritative Movement to sync all player input with the server.Server Authoritative Movement

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Player Rotation</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
<tr><td>Player Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Move Vector</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
<tr><td>Player's Head Rotation</td><td>float</td></tr>
<tr><td>Input Data</td><td>unsigned varint64</td></tr>
<tr><td>Input Mode</td><td>unsigned varint</td></tr>
<tr><td>Play Mode</td><td>unsigned varint</td></tr>
<tr><td>New Interaction Model</td><td>unsigned varint</td></tr>
<tr><td>Dependency on 'Play Mode == ClientPlayMode::Reality'</td><td><b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>VR Gaze Direction</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Client tick</td><td><table><tbody><tr><td>unsigned varint64</td><td>Which simulation frame client is on. Used to match corrections</td></tr></tbody></table></td></tr>
<tr><td>Pos Delta</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Dependency on 'ItemUseTransaction and PerformItemInteraction bit set'</td><td><b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Item Use Transaction</td><td><a href="../types/PackedItemUseLegacyInventoryTransaction.md">PackedItemUseLegacyInventoryTransaction</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Dependency on 'ItemStackRequest and PerformItemStackRequest bit set'</td><td><b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Client Request Id</td><td><a href="../types/TypedClientNetId_ItemStackRequestIdTag.md">TypedClientNetId<struct ItemStackRequestIdTag,int,0></a></td></tr>
  <tr><td>Actions</td><td><b>Array Size:</b> unsigned varint
    There are a variety of possible actions each with their own schema; this (Take) is just one example. Refer to the Item Stack Net Manager documentation.  
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Action type</td><td>byte</td></tr>
    <tr><td>Amount</td><td>byte</td></tr>
    <tr><td>Source</td><td><a href="../types/ItemStackRequestSlotInfo.md">ItemStackRequestSlotInfo</a></td></tr>
    <tr><td>Destination</td><td><a href="../types/ItemStackRequestSlotInfo.md">ItemStackRequestSlotInfo</a></td></tr>
    </tbody></table></td></tr>
  <tr><td>Strings To Filter</td><td><b>Array Size:</b> unsigned varint
    Array of strings to submit to profanity filtering service  
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>String To Filter</td><td><table><tbody><tr><td>string</td><td>Indivdiual string that needs checking</td></tr></tbody></table></td></tr>
    </tbody></table></td></tr>
  <tr><td>StringsToFilterOrigin</td><td>int</td></tr>
  </tbody></table></td></tr>
<tr><td>Dependency on 'PerformBlockActions bit set'</td><td><b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player Block Actions</td><td><a href="../types/PlayerBlockActions.md">PlayerBlockActions</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Dependency on 'IsInClientPredictedVehicle bit set'</td><td><b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Vehicle Rotation</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
  <tr><td>Client Predicted Vehicle</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Analog MoveVector</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
</tbody></table>