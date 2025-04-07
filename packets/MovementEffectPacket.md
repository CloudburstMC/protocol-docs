# MovementEffectPacket

__ID: 318__

These packets are sent to the client to update specific MovementEffects. These MovementEffects can be client-predicted. Ex: Fireworks Rockets used while gliding send this packet to the client so they know the exact duration of the GLIDE_BOOST MovementEffect.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Effect ID</td><td>varint</td></tr>
<tr><td>Effect Duration</td><td>varint</td></tr>
<tr><td>Tick</td><td><a href="../types/PlayerInputTick.md">PlayerInputTick</a></td></tr>
</tbody></table>