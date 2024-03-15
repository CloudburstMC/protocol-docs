# PacketViolationWarningPacket

__ID: 156__

This is sent when the client detects a malformed packet.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Violation Type</td><td><table><tbody><tr><td>varint</td><td><a href="../enums/PacketViolationType.md">PacketViolationType</a></td></tr></tbody></table></td></tr>
<tr><td>Violation Severity</td><td><table><tbody><tr><td>varint</td><td><a href="../enums/PacketViolationSeverity.md">PacketViolationSeverity</a></td></tr></tbody></table></td></tr>
<tr><td>Violating packet id</td><td><table><tbody><tr><td>varint</td><td><a href="../enums/MinecraftPacketIds.md">MinecraftPacketIds</a></td></tr></tbody></table></td></tr>
<tr><td>Violation context</td><td>string</td></tr>
</tbody></table>