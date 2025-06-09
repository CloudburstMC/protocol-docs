# LevelSettings

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Seed</td><td>unsigned int64</td></tr>
<tr><td>Spawn Settings</td><td><a href="../types/SpawnSettings.md">SpawnSettings</a></td></tr>
<tr><td>Generator Type</td><td>varint</td></tr>
<tr><td>Game Type</td><td>varint</td></tr>
<tr><td>is Hardcore Mode enabled?</td><td>bool</td></tr>
<tr><td>Game Difficulty</td><td>varint</td></tr>
<tr><td>Default Spawn Block Position</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
<tr><td>Achievements Disabled</td><td>bool</td></tr>
<tr><td>Editor World Type</td><td>varint</td></tr>
<tr><td>is Created In Editor</td><td>bool</td></tr>
<tr><td>is Exported From Editor</td><td>bool</td></tr>
<tr><td>Day Cycle Stop Time</td><td>varint</td></tr>
<tr><td>Education Edition Offer</td><td>varint</td></tr>
<tr><td>Are Education features enabled?</td><td>bool</td></tr>
<tr><td>Education product id</td><td>string</td></tr>
<tr><td>Rain Level</td><td>float</td></tr>
<tr><td>Lightning Level</td><td>float</td></tr>
<tr><td>Has confirmed Platform Locked Content</td><td>bool</td></tr>
<tr><td>Was Multiplayer intended to be enabled?</td><td>bool</td></tr>
<tr><td>Was LAN broadcasting intended to be enabled?</td><td>bool</td></tr>
<tr><td>Xbox Live Broadcast Setting</td><td>varint</td></tr>
<tr><td>Platform Broadcast Setting</td><td>varint</td></tr>
<tr><td>Commands Enabled</td><td>bool</td></tr>
<tr><td>Texture Packs Required</td><td>bool</td></tr>
<tr><td>Rule Data</td><td><a href="../types/GameRulesChangedPacketData.md">GameRulesChangedPacketData</a></td></tr>
<tr><td>Experiments</td><td><a href="../types/Experiments.md">Experiments</a></td></tr>
<tr><td>Has Bonus Chest Enabled?</td><td>bool</td></tr>
<tr><td>Start with Map Enabled?</td><td>bool</td></tr>
<tr><td>Player Permissions</td><td>varint</td></tr>
<tr><td>Server Chunk Tick Range</td><td>int</td></tr>
<tr><td>Has locked behavior pack?</td><td>bool</td></tr>
<tr><td>Has locked resource pack?</td><td>bool</td></tr>
<tr><td>Is from locked template?</td><td>bool</td></tr>
<tr><td>Use Msa Gamertags Only?</td><td>bool</td></tr>
<tr><td>Indicates if this world was created from a template.</td><td><table><tbody><tr><td>bool</td><td>For servers this should always be false.</td></tr></tbody></table></td></tr>
<tr><td>Indicates if this world is a template with locked settings.</td><td><table><tbody><tr><td>bool</td><td>For servers this should always be false.</td></tr></tbody></table></td></tr>
<tr><td>Only spawn v1 villagers</td><td>bool</td></tr>
<tr><td>PersonaDisabled?</td><td>bool</td></tr>
<tr><td>CustomSkinsDisabled?</td><td>bool</td></tr>
<tr><td>Emote Chat Muted</td><td>bool</td></tr>
<tr><td>Base Game Version</td><td><a href="../types/BaseGameVersion.md">BaseGameVersion</a></td></tr>
<tr><td>Limited World Width</td><td>int</td></tr>
<tr><td>Limited World Depth</td><td>int</td></tr>
<tr><td>Nether type</td><td>bool</td></tr>
<tr><td>Edu Shared Uri Resource</td><td><a href="../types/EduSharedUriResource.md">EduSharedUriResource</a></td></tr>
<tr><td>Override force experimental gameplay has value</td><td><table><tbody><tr><td>bool</td><td>For servers this should always be false</td></tr></tbody></table></td></tr>
<tr><td>ChatRestriction Level</td><td>byte</td></tr>
<tr><td>DisablePlayerInteractions ?</td><td>bool</td></tr>
<tr><td>Server Identifier</td><td>string</td></tr>
<tr><td>World Identifier from the server.</td><td>string</td></tr>
<tr><td>Scenario Identifier from the server.</td><td>string</td></tr>
<tr><td>Owner Identifier from the server.</td><td>string</td></tr>
</tbody></table>