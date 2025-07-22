# AddItemActorPacket

**ID: 15**  
**Purpose: Add Item Actor**  

When an item actor is added to the world (punch a tree->tree block, for example)

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Actor ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Target Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Item</td><td><a href="../types/NetworkItemStackDescriptor.md">NetworkItemStackDescriptor</a></td></tr>
<tr><td>Position</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Velocity</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
<tr><td>Entity Data</td><td><a href="../types/DataItem[].md">std::vector&lt;class std::unique_ptr&lt;class DataItem,struct std::default_delete&lt;class DataItem&gt; &gt;,class std::allocator&lt;class std::unique_ptr&lt;class DataItem,struct std::default_delete&lt;class DataItem&gt; &gt; &gt; &gt;</a></td></tr>
<tr><td>From Fishing?</td><td>bool</td></tr>
</tbody></table>