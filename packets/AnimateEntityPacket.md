# AnimateEntityPacket

**ID: 158**  
**Purpose: AnimateEntityPacket**  

The AnimateEntityPacket is used to trigger a one-off animation on the client it is sent to.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>mAnimation</td><td><table><tbody><tr><td>string</td><td>The name of the animation that the specified entities are to play.</td></tr></tbody></table></td></tr>
<tr><td>mNextState</td><td><table><tbody><tr><td>string</td><td>The next state to transition to once the specified animation is finished playing.</td></tr></tbody></table></td></tr>
<tr><td>mStopExpression</td><td>string</td></tr>
<tr><td>Stop expression molang version</td><td>int</td></tr>
<tr><td>mController</td><td><table><tbody><tr><td>string</td><td>The name of an animation controller</td></tr></tbody></table></td></tr>
<tr><td>mBlendOutTime</td><td><table><tbody><tr><td>float</td><td>The amount of time to blend out of this animation</td></tr></tbody></table></td></tr>
<tr><td>mRuntimeIds</td><td><b>List Size:</b> unsigned varint
  ActorRuntimeIDs of the entities that will play the specified animation  
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>runtimeId</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>