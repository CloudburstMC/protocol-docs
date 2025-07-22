# CommandRequestPacket

**ID: 77**  
**Purpose: Command Request**  

"slash" command execution, client to server.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Command</td><td>string</td></tr>
<tr><td>Command Origin</td><td><a href="../types/CommandOriginData.md">CommandOriginData</a></td></tr>
<tr><td>Is Internal Source?</td><td>bool</td></tr>
<tr><td>Version</td><td>varint</td></tr>
</tbody></table>