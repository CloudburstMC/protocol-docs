# HurtArmorPacket

**ID: 38**  
**Purpose: Hurt Armor**  

Sends the damage taken after armor is taken into account. This looks like it is trying to be phased out, this is not sent while the ItemStackNetManagerServer is active. From the server.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Cause</td><td>varint</td></tr>
<tr><td>Damage</td><td>varint</td></tr>
<tr><td>Armor Slots</td><td><table><tbody><tr><td>unsigned varint64</td><td>Bitset</td></tr></tbody></table></td></tr>
</tbody></table>