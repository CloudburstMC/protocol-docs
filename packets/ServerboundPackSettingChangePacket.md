# ServerboundPackSettingChangePacket

**ID: 329**  
**Purpose: Sent from the client to the server when players change Pack Settings (pack UI).**  

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>PackId</td><td><table><tbody><tr><td>Most Significant Bits</td><td>The UUID of the pack whose setting is being changed.</td></tr></tbody></table></td></tr>
<tr><td>PackSettingName</td><td><table><tbody><tr><td>string</td><td>The name of the setting being changed.</td></tr></tbody></table></td></tr>
<tr><td>PackSettingValue</td><td><table><tbody><tr><td></td><td>The value of the setting being changed.</td></tr></tbody></table></td></tr>
</tbody></table>