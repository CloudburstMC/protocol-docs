# MotionPredictionHintsPacket

**ID: 157**  
**Purpose: It is essentially a SetActionMotionPacket with a bool indicating if the actor was on the ground at the time the packet is sent or not.**  

This is from the server when spatial optimizations are enabled and the server does not send a spatial update.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>mRuntimeId</td><td><table><tbody><tr><td>Actor Runtime ID</td><td>Id of moving actor</td></tr></tbody></table></td></tr>
<tr><td>mMotion</td><td><table><tbody><tr><td>X</td><td>Position delta</td></tr></tbody></table></td></tr>
<tr><td>mOnGround</td><td><table><tbody><tr><td>bool</td><td>Not falling / jumping</td></tr></tbody></table></td></tr>
</tbody></table>