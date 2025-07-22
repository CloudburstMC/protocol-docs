# PacketViolationWarningPacket

**ID: 156**  
**Purpose: This is sent when the client detects a malformed packet**  

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Violation Type</td><td>enum PacketViolationType</td></tr>
<tr><td>Violation Severity</td><td>enum PacketViolationSeverity</td></tr>
<tr><td>Violation PacketId</td><td>varint</td></tr>
<tr><td>Violation Context</td><td>string</td></tr>
</tbody></table>