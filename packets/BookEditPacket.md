# BookEditPacket

**ID: 97**  
**Purpose: Book Edit**  

Sends the updated state of the book and quill item from client to server during use, i.e. before you sign it, making it uneditible.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Action</td><td>byte</td></tr>
<tr><td>Book Slot</td><td>byte</td></tr>
<tr><td>Dependency on 'Action'</td><td><b>ReplacePage</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Page Index</td><td>byte</td></tr>
  <tr><td>Text 1</td><td>string</td></tr>
  <tr><td>Text 2</td><td>string</td></tr>
  </tbody></table><hr>
  <b>AddPage</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Page Index</td><td>byte</td></tr>
  <tr><td>Text 1</td><td>string</td></tr>
  <tr><td>Text 2</td><td>string</td></tr>
  </tbody></table><hr>
  <b>DeletePage</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Page Index</td><td>byte</td></tr>
  </tbody></table><hr>
  <b>SwapPages</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Page Index A</td><td>byte</td></tr>
  <tr><td>Page Index B</td><td>byte</td></tr>
  </tbody></table><hr>
  <b>Finalize</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Text A</td><td>string</td></tr>
  <tr><td>Text B</td><td>string</td></tr>
  <tr><td>XUID</td><td>string</td></tr>
  </tbody></table></td></tr>
</tbody></table>