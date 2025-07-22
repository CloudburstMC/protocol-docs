# FeatureRegistryPacket

**ID: 191**  
**Purpose: FeatureRegistryPacket**  

This is the packet that tracks the active feature registry data from the server so that client can place the features themselves.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>FeaturesDataList</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>feature Name</td><td>string</td></tr>
  <tr><td>Binary Json Output</td><td>string</td></tr>
  </tbody></table></td></tr>
</tbody></table>