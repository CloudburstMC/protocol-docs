# ClientMovementPredictionSyncPacket

**ID: 322**  
**Purpose: Sends client movement prediction information to the server**  

Only used in Server-Authoritative Movement. Sent periodically if the client has received corrections from the server. Contains information about client-predictions that are relevant to movement.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Actor Data Flag</td><td><a href="../types/ActorDataFlagComponent.md">ActorDataFlagComponent</a></td></tr>
<tr><td>Actor Bounding Box</td><td><a href="../types/ActorDataBoundingBoxComponent.md">ActorDataBoundingBoxComponent</a></td></tr>
<tr><td>Movement Attributes</td><td><a href="../types/MovementAttributesComponent.md">MovementAttributesComponent</a></td></tr>
<tr><td>Actor Unique ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Actor Flying State</td><td><a href="../types/bool.md">bool</a></td></tr>
</tbody></table>