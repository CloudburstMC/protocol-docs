# UpdateBlockSyncedPacket

**ID: 110**  
**Purpose: Used to sync moving blocks with clients so they render correctly**  

Variation of UpdateBlockSyncedPacket that includes information to sync entities with renderchunk generation. Occasionally when blocks change a sync message is sent and during the change on the dimension, this packet is sent to the client to alert the update flags and sync info at a specific position.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Block Position</td><td>X</td></tr>
<tr><td>Block Runtime ID</td><td>unsigned varint</td></tr>
<tr><td>Flags</td><td>unsigned varint</td></tr>
<tr><td>Layer</td><td>unsigned varint</td></tr>
<tr><td>Unique Actor Id</td><td><table><tbody><tr><td>unsigned varint64</td><td>Id for the Moving Block Actor</td></tr></tbody></table></td></tr>
<tr><td>Actor Sync Message</td><td>unsigned varint64</td></tr>
</tbody></table>