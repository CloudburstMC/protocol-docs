# ResourcePacksInfoPacket

**ID: 6**  
**Purpose: Resource Packs Info**  

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Resource Pack Required</td><td>bool</td></tr>
<tr><td>Has Addon Packs</td><td>bool</td></tr>
<tr><td>Has Scripts</td><td>bool</td></tr>
<tr><td>Force Disable Vibrant Visuals</td><td><table><tbody><tr><td>bool</td><td>Whether the client should disable Vibrant Visuals when connecting to the server.</td></tr></tbody></table></td></tr>
<tr><td>World Template UUID</td><td><a href="../types/mce_UUID.md">mce::UUID</a></td></tr>
<tr><td>World Template Version</td><td><table><tbody><tr><td>string</td><td>Indicates the version of the template used to create the world on the server.</td></tr></tbody></table></td></tr>
<tr><td>Resource Packs</td><td><b>Resource Packs Size:</b> unsigned short
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Pack Id Version Id</td><td><a href="../types/mce_UUID.md">mce::UUID</a></td></tr>
  <tr><td>Pack Id Version Version</td><td>string</td></tr>
  <tr><td>Pack Size</td><td>unsigned int64</td></tr>
  <tr><td>Content Key</td><td>string</td></tr>
  <tr><td>Subpack Name</td><td>string</td></tr>
  <tr><td>Content Identity</td><td>string</td></tr>
  <tr><td>Has Scripts</td><td>bool</td></tr>
  <tr><td>Is Addon Pack</td><td><table><tbody><tr><td>bool</td><td>Indicates this pack is part of an Add-On. Helps clients determine if the pack must be downloaded to join the server as Add-On packs are required to play without issues.</td></tr></tbody></table></td></tr>
  <tr><td>Is Ray Tracing Capable</td><td>bool</td></tr>
  <tr><td>CDN URL</td><td>string</td></tr>
  </tbody></table></td></tr>
</tbody></table>