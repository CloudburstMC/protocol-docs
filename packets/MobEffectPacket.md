# MobEffectPacket

__ID: 28__

At the start of the game the server sends any mob effects with _sendAdditionalLevelData() if the joining player saved out with them,

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Event ID</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/MobEffectPacket_Event.md">MobEffectPacket::Event</a></td></tr></tbody></table></td></tr>
<tr><td>Effect ID</td><td>varint</td></tr>
<tr><td>Effect Amplifier</td><td>varint</td></tr>
<tr><td>Show Particles</td><td>bool</td></tr>
<tr><td>Effect Duration Ticks</td><td>varint</td></tr>
<tr><td>Tick</td><td>unsigned int64</td></tr>
</tbody></table>