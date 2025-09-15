# AnimateEntityPacket

**ID: 158**  
**Purpose: The AnimateEntityPacket is used to trigger a one - off animation on the client it is sent to.**  

Several properties can be specified in the following order: - The name of the animation (a string) that the specified entities are to play. - The next state to transition to (a string) once the specified animation is finished playing. - The stop expression (a string), the condition that determines when to transition to the next state. - The name of an animation controller (a string) that you would like to use. - The blend out time (a float), the amount of time to blend out of this animation. - A vector of ActorRuntimeIds of the entities that will play the specified animation.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>mAnimation</td><td>string</td></tr>
<tr><td>mNextState</td><td>string</td></tr>
<tr><td>mStopExpression</td><td>string</td></tr>
<tr><td>mStopExpressionVersion</td><td>int</td></tr>
<tr><td>mController</td><td>string</td></tr>
<tr><td>mBlendOutTime</td><td>float</td></tr>
<tr><td>mRuntimeIds</td><td>List Size</td></tr>
</tbody></table>