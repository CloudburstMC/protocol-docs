# AddPlayerPacket

**ID: 12**  
**Purpose: Add Player**  

A new player joins the game; the server sends this packet to the *other* players.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>UUID</td><td><a href="../types/mce_UUID.md">mce::UUID</a></td></tr>
<tr><td>Player Name</td><td>string</td></tr>
<tr><td>Target Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Platform Chat Id</td><td>string</td></tr>
<tr><td>Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Velocity</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Rotation</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
<tr><td>Y-Head Rotation</td><td>float</td></tr>
<tr><td>Carried Item</td><td><a href="../types/NetworkItemStackDescriptor.md">NetworkItemStackDescriptor</a></td></tr>
<tr><td>Player Game Type</td><td>varint</td></tr>
<tr><td>Dependency on 'SynchedActorDataEntityWrapper exist?'</td><td><b>If False</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Unpack</td><td><a href="../types/DataItem[].md">std::vector&lt;class std::unique_ptr&lt;class DataItem,struct std::default_delete&lt;class DataItem&gt; &gt;,class std::allocator&lt;class std::unique_ptr&lt;class DataItem,struct std::default_delete&lt;class DataItem&gt; &gt; &gt; &gt;</a></td></tr>
  </tbody></table><hr>
  <b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Entity Data PackAll</td><td><a href="../types/DataItem[].md">std::vector&lt;class std::unique_ptr&lt;class DataItem,struct std::default_delete&lt;class DataItem&gt; &gt;,class std::allocator&lt;class std::unique_ptr&lt;class DataItem,struct std::default_delete&lt;class DataItem&gt; &gt; &gt; &gt;</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Synched Properties</td><td><a href="../types/PropertySyncData.md">PropertySyncData</a></td></tr>
<tr><td>AbilitiesData</td><td><a href="../types/SerializedAbilitiesData.md">SerializedAbilitiesData</a></td></tr>
<tr><td>Actor Links</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Link</td><td><a href="../types/ActorLink.md">ActorLink</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Device Id</td><td><table><tbody><tr><td>string</td><td>A unique device id obtained from the connection request.</td></tr></tbody></table></td></tr>
<tr><td>Build Platform</td><td>int</td></tr>
</tbody></table>