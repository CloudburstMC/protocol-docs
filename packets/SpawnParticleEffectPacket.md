# SpawnParticleEffectPacket

**ID: 118**  
**Purpose: SpawnParticleEffectPacket**  

This is not used for much anymore, only the Particle command (spawn particle by name at a location) and for

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Dimension Id</td><td>byte</td></tr>
<tr><td>Actor Id</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Effect Name</td><td><table><tbody><tr><td>string</td><td>Should be an effect that exists on the client. No-op if the effect doesn't exist.</td></tr></tbody></table></td></tr>
<tr><td>Molang Variables</td><td><a href="../types/Optional_class MolangVariableMap.md">std::optional&lt;class MolangVariableMap&gt;</a></td></tr>
</tbody></table>