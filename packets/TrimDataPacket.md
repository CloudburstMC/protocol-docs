# TrimDataPacket

**ID: 302**  
**Purpose: TrimDataPacket**  

Sent from the server on level startup to send all trim patterns to the client.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>TrimPattern List</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Item Name</td><td>string</td></tr>
  <tr><td>Pattern Id</td><td>string</td></tr>
  </tbody></table></td></tr>
<tr><td>TrimMaterial List</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Material Id</td><td>string</td></tr>
  <tr><td>Color</td><td>string</td></tr>
  <tr><td>Item Name</td><td>string</td></tr>
  </tbody></table></td></tr>
</tbody></table>