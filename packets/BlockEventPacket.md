# BlockEventPacket

__ID: 26__

Whenever a block event happens it is sent from the server to sync client and server, with arbitrarily encoded information in b0 and b1.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Block Position</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
<tr><td>Event Type</td><td>varint</td></tr>
<tr><td>Event Value</td><td>varint</td></tr>
</tbody></table>