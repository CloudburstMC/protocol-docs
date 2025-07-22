# CameraAimAssistPresetsPacket

**ID: 320**  
**Purpose: Camera aim-assist registry presets/categories data sent from the server to clients.**  

Sent by the server to clients for initializing and updating the client aim-assist registry. AddToExisting operations are sent by the server when new presets/categories are added to the registry through creator facing APIs.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Camera Aim-Assist Categories</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Category</td><td><a href="../types/SharedTypes_v1_21_50_CameraAimAssistCategoryDefinition.md">SharedTypes::v1_21_50::CameraAimAssistCategoryDefinition</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Camera Aim-Assist Presets</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Preset</td><td><a href="../types/SharedTypes_v1_21_50_CameraAimAssistPresetDefinition.md">SharedTypes::v1_21_50::CameraAimAssistPresetDefinition</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Operation</td><td>byte</td></tr>
</tbody></table>