# RemoveActorPacket

**ID: 14**  
**Purpose: Occasionally, during the server player tick some time is taken to remove nearby actors from the world.**  

This is sent to the client to confirm which entity is being removed. This is done by sending an ActorUniqueID

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Actor ID</td><td>Actor Unique ID</td></tr>
</tbody></table>