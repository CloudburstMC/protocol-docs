# NetworkItemInstanceDescriptor

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Dependency on 'Valid item'</td><td><b>if (0)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Id</td><td><table><tbody><tr><td>varint</td><td>Send fixed Id of 0 for invalid item</td></tr></tbody></table></td></tr>
  </tbody></table><hr>
  <b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Id</td><td>varint</td></tr>
  <tr><td>Stack size</td><td>unsigned short</td></tr>
  <tr><td>Aux value</td><td>unsigned varint</td></tr>
  <tr><td>Block Runtime Id</td><td>varint</td></tr>
  <tr><td>User Data Buffer</td><td>string</td></tr>
  </tbody></table></td></tr>
</tbody></table>