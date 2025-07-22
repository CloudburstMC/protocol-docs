# AvailableCommandsPacket

**ID: 76**  
**Purpose: Available Commands**  

This very large packet (>10k) sends the available slash commands as part of the login process.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Enum Values</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Value</td><td>string</td></tr>
  </tbody></table></td></tr>
<tr><td>Chained Subcommand Values</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Chained Subcommand Value</td><td>string</td></tr>
  </tbody></table></td></tr>
<tr><td>Post Fixes</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Post Fix</td><td>string</td></tr>
  </tbody></table></td></tr>
<tr><td>Enum Data</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Name</td><td>string</td></tr>
  <tr><td>Values</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Dependency on '1, 2 or 4 Bytes Unsigned'</td><td><b>Enum Values Size <= 256</b><br>
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Enum Value</td><td>byte</td></tr>
      </tbody></table><hr>
      <b>Enum Values Size <= 65536</b><br>
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Enum Value</td><td>unsigned short</td></tr>
      </tbody></table><hr>
      <b>Default</b><br>
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Enum Value</td><td>unsigned int</td></tr>
      </tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Chained Subcommand Data</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>SubCommand Name</td><td>string</td></tr>
  <tr><td>SubCommand values</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>SubCommand First Value</td><td>unsigned short</td></tr>
    <tr><td>SubCommand Second Value</td><td>unsigned short</td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Commands</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Name</td><td>string</td></tr>
  <tr><td>Description</td><td>string</td></tr>
  <tr><td>Flags</td><td>unsigned short</td></tr>
  <tr><td>Permission Level</td><td>byte</td></tr>
  <tr><td>Alias Enum</td><td>int</td></tr>
  <tr><td>CommandData Chained Subcommand Indexes</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Index</td><td>unsigned short</td></tr>
    </tbody></table></td></tr>
  <tr><td>Overloads</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>isChaining</td><td>bool</td></tr>
    <tr><td>Parameter Data</td><td><b>List Size:</b> unsigned varint
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Name</td><td>string</td></tr>
      <tr><td>Parse Symbol</td><td>unsigned int</td></tr>
      <tr><td>Is Optional?</td><td>bool</td></tr>
      <tr><td>Options</td><td>byte</td></tr>
      </tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Soft Enums</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Enum Name</td><td>string</td></tr>
  <tr><td>Enum Options</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Value</td><td>string</td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Constraints</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Enum Value Symbol</td><td><table><tbody><tr><td>unsigned int</td><td>Symbol in the command parser representing this enum's value.</td></tr></tbody></table></td></tr>
  <tr><td>Enum Symbol</td><td><table><tbody><tr><td>unsigned int</td><td>Symbol in the command parser representing this enum.</td></tr></tbody></table></td></tr>
  <tr><td>Constraint Indices</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Semantic Constraint Index</td><td><table><tbody><tr><td>byte</td><td>Index of the semantic constraint within the command parser.</td></tr></tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>