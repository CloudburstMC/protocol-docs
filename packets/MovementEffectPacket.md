# MovementEffectPacket

**ID: 318**  
**Purpose: These packets are sent to the client to update specific MovementEffects**  

These MovementEffects can be client-predicted. Ex: Fireworks Rockets used while gliding send this packet to the client so they know the exact duration of the GLIDE_BOOST MovementEffect.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Runtime ID</td><td>Actor Runtime ID</td></tr>
<tr><td>Effect ID</td><td>enum MovementEffectType</td></tr>
<tr><td>Effect Duration</td><td>varint</td></tr>
<tr><td>Tick</td><td>Input tick</td></tr>
</tbody></table>