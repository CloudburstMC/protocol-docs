# PlayerAuthInputPacket

**ID: 144**  
**Purpose: Player Auth Input**  

These are for Server Authoritative Movement to sync all player input with the server. - PlayerActionPacket (one-off actions) - MovePlayerPacket (primary input) - MoveActorAbsolutePacket (positioning client authoritative vehicles) - AnimatePacket (For client to server, it is only used for swing) - InventoryTransactionPacket (item use) The server can force reposition on the client using these: - MovePlayerPacket - CorrectPlayerMovePredictionPacket - SetActorMotionPacket Additionally, in this mode many client-bound packets have a 'Tick' value. These echo back the tick value that the client supplies in the PlayerAuthInputPacket. For packets relating to a player or client predicted vehicle, the tick value should be that of the most recently processed PlayerAuthInputPacket from the player. Specifying zero is also acceptable although may result in minor visual flickering as it may confuse client predicted actions. The jump scale (progress bar for horse jumping) is computed like this: - Jump ticks start accumulating when `InputData::Jumping` is set in `PlayerAuthInputPacket` - Every following tick that `InputData::Jumping` is still set the jump ticks increase by 1 - The first tick that releases `InputData::Jumping` expects the jump to trigger, producing the jump scale using this formula floor((ticks < 10.0f ? ticks x 0.1f : 0.8f + (2.0f / (ticks - 9.0f)) x 0.1f) x 100.0) Boat paddling determines the ActorDataIDs::ROW_TIME_LEFT and ROW_TIME_RIGHT like this: Every tick the row time is incremented on that side if it is paddling. Paddle input is determined in two different ways depending on input mode. 'Paddle force' mode is used if: - `PlayerAuthInputPacket::mInputMode` is anything other than `InputMode::Touch` - `PlayerAuthInputPacket::mPlayMode` is `ClientPlayMode::Reality` (VR) - `PlayerAuthInputPacket::mNewInteractionModel` is `NewInteractionModel::Touch` or `NewInteractionModel::Classic` Paddle force mode Paddle force uses the `PlayerAuthInputPacket::mMove` direction to paddle the boat relative to its orientation like in keyboard mode. Left will paddle the left oar meaning the boat turns right. This means the paddle state can be implied from `mMove`: - Left is paddling if `mMove.y` is nonzero or `mMove.x` is negative - Right is paddling if `mMove.y` is nonzero or `mMove.x` is positive Non paddle force mode - Left is paddling if `InputData::PaddlingLeft` is set - Right is paddling if `InputData::PaddlingRight` is set Adopting server authoritative movement protocol This packet can be used to implement client authoritative motion by blindly accepting the Player Position and Rotation values except for the caveat described in PlayerActionType::HandledTeleport. If they are riding a client predicted vehicle as determined by a previous SetActorLinkPacket from the server, the position and velocity is interpreted as the vehicle, not the player. If desired, the server can additionally simulate motion and send CorrectPlayerMovePredictionPackets rather than accepting client reported positions. The server may also reject the InputData state transitions usually by sending a corrective SetActorDataPacket, see the PlayerAuthInputPacket::InputData enum table for details. All tick values for client bound packets that have them should be written as specified in the documentation on PlayerInputTick.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Player Rotation</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
<tr><td>Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Move Vector</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
<tr><td>Player's Head Rotation</td><td><table><tbody><tr><td>float</td><td>Effectively the same as the Y component of Player Rotation</td></tr></tbody></table></td></tr>
<tr><td>Input Data</td><td><a href="../types/std_bitset<65>.md">std::bitset&lt;65&gt;</a></td></tr>
<tr><td>Input Mode</td><td>unsigned varint</td></tr>
<tr><td>Play Mode</td><td>unsigned varint</td></tr>
<tr><td>New Interaction Model</td><td>unsigned varint</td></tr>
<tr><td>Interact Rotation</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
<tr><td>Client tick</td><td><a href="../types/PlayerInputTick.md">PlayerInputTick</a></td></tr>
<tr><td>Pos Delta</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Dependency on 'ItemUseTransaction and PerformItemInteraction bit set'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Item Use Transaction</td><td><a href="../types/PackedItemUseLegacyInventoryTransaction.md">PackedItemUseLegacyInventoryTransaction</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Dependency on 'ItemStackRequest and PerformItemStackRequest bit set'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Client Request Id</td><td><a href="../types/TypedClientNetId_ItemStackRequestIdTag.md">TypedClientNetId&lt;struct ItemStackRequestIdTag,int,0&gt;</a></td></tr>
  <tr><td>Actions</td><td><b>List Size:</b> unsigned varint
    There are a variety of possible actions each with their own schema; this (Take) is just one example. Refer to the Item Stack Net Manager documentation.  
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Action type</td><td>byte</td></tr>
    <tr><td>Amount</td><td>byte</td></tr>
    <tr><td>Source</td><td><a href="../types/ItemStackRequestSlotInfo.md">ItemStackRequestSlotInfo</a></td></tr>
    <tr><td>Destination</td><td><a href="../types/ItemStackRequestSlotInfo.md">ItemStackRequestSlotInfo</a></td></tr>
    </tbody></table></td></tr>
  <tr><td>Strings To Filter</td><td><b>List Size:</b> unsigned varint
    Array of strings to submit to profanity filtering service  
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>String To Filter</td><td><table><tbody><tr><td>string</td><td>Indivdiual string that needs checking</td></tr></tbody></table></td></tr>
    </tbody></table></td></tr>
  <tr><td>StringsToFilterOrigin</td><td>int</td></tr>
  </tbody></table></td></tr>
<tr><td>Dependency on 'PerformBlockActions bit set'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player Block Actions</td><td><a href="../types/PlayerBlockActions.md">PlayerBlockActions</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Dependency on 'IsInClientPredictedVehicle bit set'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Vehicle Rotation</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
  <tr><td>Client Predicted Vehicle</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Analog MoveVector</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
<tr><td>Camera Orientation</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Raw MoveVector</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
</tbody></table>