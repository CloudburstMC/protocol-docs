# SpawnParticleEffectPacket

**ID: 118**  
**Purpose: Tell client to spawn a particle effect.**  

This is not used for much anymore, only the Particle command (spawn particle by name at a location) and for ScriptServerSpawnParticleAttachedToActor and ScriptServerSpawnParticleInWorldEvent.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Dimension Id</td><td>unsigned byte</td></tr>
<tr><td>Actor Id</td><td>Actor Unique ID</td></tr>
<tr><td>Position</td><td>X</td></tr>
<tr><td>Effect Name</td><td><table><tbody><tr><td>string</td><td>Should be an effect that exists on the client. No-op if the effect doesn't exist.</td></tr></tbody></table></td></tr>
<tr><td>Molang Variables</td><td>Molang Variables</td></tr>
</tbody></table>