# AvailableActorIdentifiersPacket

**ID: 119**  
**Purpose: Available Actor Identifiers**  

On world start, send clients the info for all available actors.Sends the whole list of actor identifiers at game start from the server.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>CompoundTag containing a list of ActorInfo: 		rid (RuntimeId - Int), 		id (string), 		bid (BaseId - string), 		hasspawnegg (bool), 		summonable (bool)</td><td><a href="../types/CompoundTag.md">CompoundTag</a></td></tr>
</tbody></table>