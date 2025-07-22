# StartGamePacket

**ID: 11**  
**Purpose: Start Game**  

Sent from the server to client when the game is starting (or client joins), gives ids and current tick. The player movement mode is also specified here, see ServerAuthMovementMode enum documentation for details on the modes.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Entity ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Game Type</td><td>varint</td></tr>
<tr><td>Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Rotation</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
<tr><td>Settings</td><td><a href="../types/LevelSettings.md">LevelSettings</a></td></tr>
<tr><td>Level ID</td><td>string</td></tr>
<tr><td>Level Name</td><td>string</td></tr>
<tr><td>Template Content Identity</td><td>string</td></tr>
<tr><td>Is Trial?</td><td>bool</td></tr>
<tr><td>Movement Settings</td><td><a href="../types/SyncedPlayerMovementSettings.md">SyncedPlayerMovementSettings</a></td></tr>
<tr><td>Level Current Time</td><td>unsigned int64</td></tr>
<tr><td>Enchantment Seed</td><td>varint</td></tr>
<tr><td>Block Properties</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Block Name</td><td>string</td></tr>
  <tr><td>Block Definition</td><td><a href="../types/CompoundTag.md">CompoundTag</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Multiplayer Correlation Id</td><td><table><tbody><tr><td>string</td><td>A UUID to identify this multiplayer session.</td></tr></tbody></table></td></tr>
<tr><td>Enable Item Stack Net Manager</td><td><table><tbody><tr><td>bool</td><td>Whether the new item stack net manager is enabled for server authoritative inventory. This will eventually be required.</td></tr></tbody></table></td></tr>
<tr><td>Server version</td><td><table><tbody><tr><td>string</td><td>For telemetry purposes - sending your own string with your own server name and version here would be useful for Mojang's telemetry.</td></tr></tbody></table></td></tr>
<tr><td>Player Property Data</td><td><a href="../types/CompoundTag.md">CompoundTag</a></td></tr>
<tr><td>Server Block Type Registry Checksum</td><td><table><tbody><tr><td>unsigned int64</td><td>Checksum for detecting mismatches in block types between server and client.</td></tr></tbody></table></td></tr>
<tr><td>World Template ID</td><td><a href="../types/mce_UUID.md">mce::UUID</a></td></tr>
<tr><td>Server Enabled ClientSide Generation</td><td><table><tbody><tr><td>bool</td><td>BiomeComponentFactory needs to know about this toggle before we start parsing BiomeComponents</td></tr></tbody></table></td></tr>
<tr><td>BlockNetworkIds Are Hashes</td><td>bool</td></tr>
<tr><td>TickDeathSystems Enabled</td><td><table><tbody><tr><td>bool</td><td>Whether the new tick death systems are enabled. This will eventually be required.</td></tr></tbody></table></td></tr>
<tr><td>NetworkPermissions</td><td><a href="../types/NetworkPermissions.md">NetworkPermissions</a></td></tr>
</tbody></table>