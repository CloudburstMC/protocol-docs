# DataItem

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>ID</td><td>unsigned varint</td></tr>
<tr><td>Type</td><td>unsigned varint</td></tr>
<tr><td>Dependency on 'Type'</td><td><b>if (0)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Value</td><td>byte</td></tr>
  </tbody></table><hr>
  <b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Value</td><td>short</td></tr>
  </tbody></table><hr>
  <b>if (2)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Value</td><td>varint</td></tr>
  </tbody></table><hr>
  <b>if (3)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Value</td><td>float</td></tr>
  </tbody></table><hr>
  <b>if (4)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Value</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (5)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Value</td><td><a href="../types/CompoundTag.md">CompoundTag</a></td></tr>
  </tbody></table><hr>
  <b>if (6)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Value</td><td><a href="../types/BlockPos.md">BlockPos</a></td></tr>
  </tbody></table><hr>
  <b>if (7)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Value</td><td>varint64</td></tr>
  </tbody></table><hr>
  <b>if (8)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Value</td><td><a href="../types/Vec3.md">Vec3</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>