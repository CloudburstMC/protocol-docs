# BookEditPacket

__ID: 97__

Sends the updated state of the book and quill item from client to server during use, i.e. before you sign it, making it uneditible.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Action</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/BookEditAction.md">BookEditAction</a></td></tr></tbody></table></td></tr>
<tr><td>Book Slot</td><td>byte</td></tr>
<tr><td>Dependency on 'Action'</td><td><b>if (0)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Page Index</td><td>byte</td></tr>
  <tr><td>Text A</td><td>string</td></tr>
  <tr><td>Text B</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Page Index</td><td>byte</td></tr>
  <tr><td>Text A</td><td>string</td></tr>
  <tr><td>Text B</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (2)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Page Index</td><td>byte</td></tr>
  </tbody></table><hr>
  <b>if (3)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Page Index A</td><td>byte</td></tr>
  <tr><td>Page Index B</td><td>byte</td></tr>
  </tbody></table><hr>
  <b>if (4)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Text A</td><td>string</td></tr>
  <tr><td>Text B</td><td>string</td></tr>
  <tr><td>XUID</td><td>string</td></tr>
  </tbody></table></td></tr>
</tbody></table>