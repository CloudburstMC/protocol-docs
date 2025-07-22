# PlayerArmorDamagePacket

**ID: 149**  
**Purpose: PlayerArmorDamagePacket**  

Sent from server whenever the player's armor takes damage. This packet sends all armor data at once.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Slots Bitset</td><td>byte</td></tr>
<tr><td>Damage For Slot (Only Gets Written If Bit Is Set)</td><td>varint</td></tr>
<tr><td>Damage For Slot (Only Gets Written If Bit Is Set)</td><td>varint</td></tr>
<tr><td>Damage For Slot (Only Gets Written If Bit Is Set)</td><td>varint</td></tr>
<tr><td>Damage For Slot (Only Gets Written If Bit Is Set)</td><td>varint</td></tr>
<tr><td>Damage For Slot (Only Gets Written If Bit Is Set)</td><td>varint</td></tr>
</tbody></table>