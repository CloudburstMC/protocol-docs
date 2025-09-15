# CameraAimAssistPresetsPacket

**ID: 320**  
**Purpose: Camera aim-assist registry presets/categories data sent from the server to clients.**  

Sent by the server to clients for initializing and updating the client aim-assist registry. AddToExisting operations are sent by the server when new presets/categories are added to the registry through creator facing APIs.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Camera Aim-Assist Presets</td><td>List Size</td></tr>
<tr><td>Camera Aim-Assist Categories</td><td>List Size</td></tr>
<tr><td>Operation</td><td>enum enum CameraAimAssistPresetsPacketOperation</td></tr>
</tbody></table>