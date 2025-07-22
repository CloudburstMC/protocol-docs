# CurrentStructureFeaturePacket

**ID: 314**  
**Purpose: Informs the client of which Structure Feature they are currently occupying.**  

Sends the name of the Structure Feature the player is currently occupying to the client. If the player is not in a structure, this packet contains an empty string.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Current Structure Feature</td><td><table><tbody><tr><td>string</td><td>The identifier of the Structure Feature that the player is currently occupying. If the player is not occupying a structure then this value is an empty string.</td></tr></tbody></table></td></tr>
</tbody></table>