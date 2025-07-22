# PlayerActionPacket

**ID: 36**  
**Purpose: Sent from the client whenever the player performs an action (dashing, un-dashing, use an item, mine/hit, use a block, etc).**  

The expected actions change depending on the ServerAuthMovementMode specified in the StartGamePacket. See the PlayerActionType enum for details on which have differing behavior. See also PlayerAuthInputPacket and InventoryTransactionPacket for similar types of player actions.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Player Runtime ID</td><td>Actor Runtime ID</td></tr>
<tr><td>Action</td><td>enum PlayerActionType</td></tr>
<tr><td>Block Position</td><td>Z</td></tr>
<tr><td>Result Pos</td><td>X</td></tr>
<tr><td>Face</td><td>varint</td></tr>
</tbody></table>