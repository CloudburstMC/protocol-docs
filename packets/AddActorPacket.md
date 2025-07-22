# AddActorPacket

**ID: 13**  
**Purpose: Add Actor (a.k.a. Entity)**  

Newly created entities on server use AddActorPacket to notify clients that they exist.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Actor ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Target Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Actor Type</td><td>string</td></tr>
<tr><td>Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Velocity</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Rotation</td><td><a href="../types/Vec2.md">Vec2</a></td></tr>
<tr><td>Y Head Rotation</td><td>float</td></tr>
<tr><td>Y Body Rotation</td><td>float</td></tr>
<tr><td>Attributes List</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Attribute Name</td><td>string</td></tr>
  <tr><td>Min Value</td><td>float</td></tr>
  <tr><td>Current Value</td><td>float</td></tr>
  <tr><td>Max Value</td><td>float</td></tr>
  </tbody></table></td></tr>
<tr><td>Actor Data</td><td><a href="../types/DataItem[].md">std::vector&lt;class std::unique_ptr&lt;class DataItem,struct std::default_delete&lt;class DataItem&gt; &gt;,class std::allocator&lt;class std::unique_ptr&lt;class DataItem,struct std::default_delete&lt;class DataItem&gt; &gt; &gt; &gt;</a></td></tr>
<tr><td>Synched Properties</td><td><a href="../types/PropertySyncData.md">PropertySyncData</a></td></tr>
<tr><td>Actor Links</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Link</td><td><a href="../types/ActorLink.md">ActorLink</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>