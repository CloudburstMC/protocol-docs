# PlayerListPacket

**ID: 63**  
**Purpose: Player List**  

Sent from the Server at the start of the game or when a player is added (or if the game does a clean up of disconnected players)

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Action</td><td>byte</td></tr>
<tr><td>Entries Count (for each List)</td><td>unsigned varint</td></tr>
<tr><td>Dependency on 'Action'</td><td><b>Add</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Add Player List</td><td><table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>UUID</td><td><a href="../types/mce_UUID.md">mce::UUID</a></td></tr>
    <tr><td>Target Actor ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
    <tr><td>Player Name</td><td>string</td></tr>
    <tr><td>XBL XUID</td><td>string</td></tr>
    <tr><td>Platform Chat Id</td><td>string</td></tr>
    <tr><td>Build Platform</td><td>int</td></tr>
    <tr><td>Serialized Skin</td><td><a href="../types/SerializedSkin.md">SerializedSkin</a></td></tr>
    <tr><td>Is Teacher?</td><td>bool</td></tr>
    <tr><td>Is Host?</td><td>bool</td></tr>
    <tr><td>Is SubClient?</td><td>bool</td></tr>
    <tr><td>Player Color</td><td><a href="../types/mce_Color.md">mce::Color</a></td></tr>
    </tbody></table></td></tr>
  <tr><td>Trusted Skin List</td><td><table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Is trusted skin</td><td>bool</td></tr>
    </tbody></table></td></tr>
  </tbody></table><hr>
  <b>Remove</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Remove Player List</td><td><table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>UUID</td><td><a href="../types/mce_UUID.md">mce::UUID</a></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>