# PacketViolationWarningPacket

__ID: 156__

This is sent when the client detects a malformed packet.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Violation Type</td><td>varint</td></tr>
<tr><td>Violation Severity</td><td>varint</td></tr>
<tr><td>Violating packet id</td><td>varint</td></tr>
<tr><td>Violation context</td><td>string</td></tr>
</tbody></table>