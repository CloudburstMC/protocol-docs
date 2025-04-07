# SerializedSkin

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Id</td><td>string</td></tr>
<tr><td>PlayFab Id</td><td>string</td></tr>
<tr><td>Resource Patch</td><td>string</td></tr>
<tr><td>Skin Image Width</td><td>unsigned int</td></tr>
<tr><td>Skin Image Height</td><td>unsigned int</td></tr>
<tr><td>Skin Image Image Bytes</td><td><table><tbody><tr><td>string</td><td>Serialized into a string</td></tr></tbody></table></td></tr>
<tr><td>Animations</td><td><b>Skin Animated Images Size:</b> unsigned int
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Image Width</td><td>unsigned int</td></tr>
  <tr><td>Image Height</td><td>unsigned int</td></tr>
  <tr><td>Image Bytes</td><td><table><tbody><tr><td>string</td><td>Serialized into a string</td></tr></tbody></table></td></tr>
  <tr><td>Animation Type</td><td>unsigned int</td></tr>
  <tr><td>Frame Count</td><td>float</td></tr>
  <tr><td>Animation Expression</td><td>unsigned int</td></tr>
  </tbody></table></td></tr>
<tr><td>CapeImage Width</td><td>unsigned int</td></tr>
<tr><td>CapeImage Height</td><td>unsigned int</td></tr>
<tr><td>CapeImage ImageBytes</td><td>string</td></tr>
<tr><td>Geometry Data</td><td>string</td></tr>
<tr><td>Geometry Data Min Engine Version</td><td><table><tbody><tr><td>string</td><td>Semantic version</td></tr></tbody></table></td></tr>
<tr><td>AnimationData</td><td>string</td></tr>
<tr><td>Cape Id</td><td>string</td></tr>
<tr><td>Full Id</td><td>string</td></tr>
<tr><td>Arm Size</td><td>string</td></tr>
<tr><td>Skin Color</td><td><table><tbody><tr><td>string</td><td>to hex string</td></tr></tbody></table></td></tr>
<tr><td>Persona Pieces</td><td><b>Persona Pieces Size:</b> unsigned int
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Piece Id</td><td>string</td></tr>
  <tr><td>Piece Type</td><td>string</td></tr>
  <tr><td>Pack Id</td><td>string</td></tr>
  <tr><td>Is Default Piece</td><td>bool</td></tr>
  <tr><td>Product Id</td><td>string</td></tr>
  </tbody></table></td></tr>
<tr><td>Piece Tint Colors</td><td><b>Piece Tint Colors Size:</b> unsigned int
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Piece Type</td><td>string</td></tr>
  <tr><td>Piece Tint Colors</td><td><b>Piece Tint Color Colors Size:</b> unsigned int
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tint Color</td><td><table><tbody><tr><td>string</td><td>To hex string</td></tr></tbody></table></td></tr>
    <tr><td>Tint Color</td><td><table><tbody><tr><td>string</td><td>To hex string</td></tr></tbody></table></td></tr>
    <tr><td>Tint Color</td><td><table><tbody><tr><td>string</td><td>To hex string</td></tr></tbody></table></td></tr>
    <tr><td>Tint Color</td><td><table><tbody><tr><td>string</td><td>To hex string</td></tr></tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Is Premium Skin</td><td>bool</td></tr>
<tr><td>Is Persona Skin</td><td><table><tbody><tr><td>bool</td><td>Whether a skin is a Classic Skin or Persona Skin</td></tr></tbody></table></td></tr>
<tr><td>Is Persona Cape On Classic Skin</td><td>bool</td></tr>
<tr><td>Is Primary User</td><td>bool</td></tr>
<tr><td>Overrides Player Appearance</td><td>bool</td></tr>
</tbody></table>