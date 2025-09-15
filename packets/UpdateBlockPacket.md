# UpdateBlockPacket

**ID: 21**  
**Purpose: Occasional packets sent from server when blocks update or are ticked. (For example, when digging.)**  

This happens often. Luckily, the packets are small.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Block Position</td><td>X</td></tr>
<tr><td>Block Runtime ID</td><td>unsigned varint</td></tr>
<tr><td>Flags</td><td>unsigned varint</td></tr>
<tr><td>Layer</td><td>unsigned varint</td></tr>
</tbody></table>