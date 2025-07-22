# PlayerSkinPacket

**ID: 93**  
**Purpose: Player Skin**  

This packet is used for when the player changes the skin they are using (in game or out of game).

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>UUID</td><td><a href="../types/mce_UUID.md">mce::UUID</a></td></tr>
<tr><td>Serialized Skin</td><td><a href="../types/SerializedSkin.md">SerializedSkin</a></td></tr>
<tr><td>New Skin Name</td><td>string</td></tr>
<tr><td>Old Skin Name</td><td>string</td></tr>
<tr><td>Whether skin is trusted marketplace content</td><td>bool</td></tr>
</tbody></table>