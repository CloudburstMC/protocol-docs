# ClientCameraAimAssistPacket

**ID: 321**  
**Purpose: Client-side activation of aim-assist**  

Sent by clients to the server for activating/deactivating aim-assist. Activation uses the CameraPreset Id for server-side lookup and uses its aim_assist field for aim-assist activation settings.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Camera Preset Id</td><td>string</td></tr>
<tr><td>Action</td><td>enum ClientCameraAimAssistPacketAction</td></tr>
<tr><td>Allow aim assist</td><td>bool</td></tr>
</tbody></table>