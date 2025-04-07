# SetActorDataPacket

__ID: 39__

Regular Actor Data delta packets, sent from the level on tick, mob and actor during normal tick

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Actor Data</td><td><a href="../types/DataItem[].md">std::vector&lt;class std::unique_ptr&lt;class DataItem,struct std::default_delete&lt;class DataItem&gt; &gt;,class std::allocator&lt;class std::unique_ptr&lt;class DataItem,struct std::default_delete&lt;class DataItem&gt; &gt; &gt; &gt;</a></td></tr>
<tr><td>Synched Properties</td><td><a href="../types/PropertySyncData.md">PropertySyncData</a></td></tr>
<tr><td>Tick</td><td><table><tbody><tr><td>unsigned varint64</td><td>Which frame we're correcting; should match the tick in the Player Auth Input packet. (Can be 0 if not doing server auth movement.)</td></tr></tbody></table></td></tr>
</tbody></table>