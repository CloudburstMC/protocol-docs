# CommandOutputPacket

**ID: 79**  
**Purpose: Command Output**  

"slash" command execution, server to client.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Origin Data</td><td><a href="../types/CommandOriginData.md">CommandOriginData</a></td></tr>
<tr><td>Output Type</td><td>byte</td></tr>
<tr><td>Success Count</td><td>unsigned varint</td></tr>
<tr><td>Output Messages</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Successful?</td><td>bool</td></tr>
  <tr><td>Message ID</td><td>string</td></tr>
  <tr><td>Parameters</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Param</td><td>string</td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Dependency on 'Output Type == DataSet'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Data Set</td><td>string</td></tr>
  </tbody></table></td></tr>
</tbody></table>