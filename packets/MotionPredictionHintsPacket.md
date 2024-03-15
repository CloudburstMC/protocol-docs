# MotionPredictionHintsPacket

__ID: 157__

This is from the server when spatial optimizations are enabled and the server does not send a spatial update. It is

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>mRuntimeId</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>mMotion</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>mOnGround</td><td><table><tbody><tr><td>bool</td><td>Not falling / jumping</td></tr></tbody></table></td></tr>
</tbody></table>