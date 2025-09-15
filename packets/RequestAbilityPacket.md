# RequestAbilityPacket

**ID: 184**  
**Purpose: Sent from client to server. Used to request an ability change.**  

Once changed, the server will broadcast the updated state of abilities for that player. If the request is rejected, the caller will receive their reverted state of Abilities. Can only be used to modify the calling player. - mVariable: Info about this variable

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Ability</td><td>varint</td></tr>
<tr><td>Value Type</td><td>enum enum RequestAbilityPacketPayload_Type</td></tr>
<tr><td>Bool</td><td>bool</td></tr>
<tr><td>Float</td><td>float</td></tr>
</tbody></table>