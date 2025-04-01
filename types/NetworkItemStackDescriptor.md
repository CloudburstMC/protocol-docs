# NetworkItemStackDescriptor

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Dependency on 'Item is valid?'</td><td><b>If False</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Id</td><td>varint</td></tr>
  <tr><td>Stack size</td><td>unsigned short</td></tr>
  <tr><td>Aux value</td><td>unsigned varint</td></tr>
  <tr><td>Include Net Id</td><td>bool</td></tr>
  <tr><td>Dependency on 'Include Net Id'</td><td><b>If True</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Net Id Variant</td><td><a href="../types/ItemStackNetIdVariant.md">ItemStackNetIdVariant</a></td></tr>
    </tbody></table></td></tr>
  <tr><td>Block Runtime Id</td><td>varint</td></tr>
  <tr><td>User Data Buffer</td><td>string</td></tr>
  </tbody></table><hr>
  <b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Id</td><td><table><tbody><tr><td>varint</td><td>Send fixed Id of 0 for invalid item</td></tr></tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>