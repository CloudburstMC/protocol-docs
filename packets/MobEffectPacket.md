# MobEffectPacket

**ID: 28**  
**Purpose: Mob Effect**  

At the start of the game the server sends any mob effects with _sendAdditionalLevelData() if the joining player saved out with them, and then anytime a mob effect is added, removed, or updated this packet is sent. It is important for player movement simulation to ensure that the following effects are sent for the player or any client predicted vehicle they are in control of: - levitation - slow_falling - jump - movement_speed - movement_slowdown - weaving

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Event ID</td><td>byte</td></tr>
<tr><td>Effect ID</td><td>varint</td></tr>
<tr><td>Effect Amplifier</td><td>varint</td></tr>
<tr><td>Show Particles</td><td>bool</td></tr>
<tr><td>Effect Duration Ticks</td><td>varint</td></tr>
<tr><td>Tick</td><td><a href="../types/PlayerInputTick.md">PlayerInputTick</a></td></tr>
</tbody></table>