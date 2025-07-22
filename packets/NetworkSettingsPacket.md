# NetworkSettingsPacket

**ID: 143**  
**Purpose: Sends tunable options from host to client (compression threshold and algorithm)**  

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Compression Threshold</td><td>unsigned short</td></tr>
<tr><td>CompressionAlgorithm</td><td>enum PacketCompressionAlgorithm</td></tr>
<tr><td>Client Throttle Enabled</td><td>bool</td></tr>
<tr><td>Client Throttle Threshold</td><td>unsigned byte</td></tr>
<tr><td>Client Throttle Scalar</td><td>float</td></tr>
</tbody></table>