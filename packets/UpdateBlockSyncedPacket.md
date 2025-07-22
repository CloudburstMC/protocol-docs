# UpdateBlockSyncedPacket

**ID: 110**  
**Purpose: Update Block Synced**  

Used to sync moving blocks with clients so they render correctlyVariation of UpdateBlockPacket that includes information to sync entities with renderchunk generation.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Block Position</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
<tr><td>Block Runtime ID</td><td>unsigned varint</td></tr>
<tr><td>Flags</td><td>unsigned varint</td></tr>
<tr><td>Layer</td><td>unsigned varint</td></tr>
<tr><td>Unique Actor Id</td><td><table><tbody><tr><td>unsigned varint64</td><td>Id for the Moving Block Actor</td></tr></tbody></table></td></tr>
<tr><td>Actor Sync Message</td><td>unsigned varint64</td></tr>
</tbody></table>