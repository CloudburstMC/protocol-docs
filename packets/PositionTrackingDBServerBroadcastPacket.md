# PositionTrackingDBServerBroadcastPacket

**ID: 153**  
**Purpose: PositionTrackingDBServerBroadcastPacket**  

Server to client packet for server authoratative runtime database (with persistent LevelStorage backup) designed primarily to track lodestone stuff. See Position Tracking DB Notes.md in bedrock-docs.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Action</td><td>byte</td></tr>
<tr><td>Id</td><td><a href="../types/PositionTrackingId.md">PositionTrackingId</a></td></tr>
<tr><td>Position tracking data</td><td><a href="../types/CompoundTag.md">CompoundTag</a></td></tr>
</tbody></table>