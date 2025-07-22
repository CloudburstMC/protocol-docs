# ServerScriptDebugDrawerPacket

**ID: 328**  
**Purpose: Debug Shapes Update**  

Used by Scripting to send new, removed or modified debug shapes information to the client to be used for rendering.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Shapes</td><td><b>List Size:</b> unsigned varint
  List of shapes that have changed  
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>NetworkId</td><td><table><tbody><tr><td>unsigned varint64</td><td>uint64 network id used to identify the matching shape on the client as the server</td></tr></tbody></table></td></tr>
  <tr><td>Shape Type</td><td><a href="../types/Optional_enum ScriptModuleDebugUtilities_ScriptDebugShapeType.md">std::optional&lt;enum ScriptModuleDebugUtilities::ScriptDebugShapeType&gt;</a></td></tr>
  <tr><td>Location</td><td><a href="../types/Optional_class Vec3.md">std::optional&lt;class Vec3&gt;</a></td></tr>
  <tr><td>Scale</td><td><a href="../types/Optional_float.md">std::optional&lt;float&gt;</a></td></tr>
  <tr><td>Rotation</td><td><a href="../types/Optional_class Vec3.md">std::optional&lt;class Vec3&gt;</a></td></tr>
  <tr><td>Total Time Left</td><td><a href="../types/Optional_float.md">std::optional&lt;float&gt;</a></td></tr>
  <tr><td>Color</td><td><a href="../types/Optional_class mce_Color.md">std::optional&lt;class mce::Color&gt;</a></td></tr>
  <tr><td>Text</td><td><a href="../types/Optional_String.md">std::optional&lt;class std::basic_string&lt;char,struct std::char_traits&lt;char&gt;,class std::allocator&lt;char&gt; &gt; &gt;</a></td></tr>
  <tr><td>Box Bound</td><td><a href="../types/Optional_class Vec3.md">std::optional&lt;class Vec3&gt;</a></td></tr>
  <tr><td>Line End Location</td><td><a href="../types/Optional_class Vec3.md">std::optional&lt;class Vec3&gt;</a></td></tr>
  <tr><td>Arrow Head Length</td><td><a href="../types/Optional_float.md">std::optional&lt;float&gt;</a></td></tr>
  <tr><td>Arrow Head Radius</td><td><a href="../types/Optional_float.md">std::optional&lt;float&gt;</a></td></tr>
  <tr><td>Num Segments</td><td><a href="../types/Optional_unsigned char.md">std::optional&lt;unsigned char&gt;</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>