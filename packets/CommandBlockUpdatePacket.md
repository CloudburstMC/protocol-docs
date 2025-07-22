# CommandBlockUpdatePacket

**ID: 78**  
**Purpose: Command Block Update**  

Sent when you close the command block screen on the client

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Is Block?</td><td>bool</td></tr>
<tr><td>Dependency on 'Is Block?'</td><td><b>If False</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Target Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
  </tbody></table><hr>
  <b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Block Position</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
  <tr><td>Command Block Mode</td><td>unsigned varint</td></tr>
  <tr><td>Redstone Mode</td><td>bool</td></tr>
  <tr><td>Is Conditional?</td><td>bool</td></tr>
  </tbody></table></td></tr>
<tr><td>Command</td><td>string</td></tr>
<tr><td>Last Output</td><td>string</td></tr>
<tr><td>Name</td><td>string</td></tr>
<tr><td>FilteredName</td><td>string</td></tr>
<tr><td>Track Output?</td><td>bool</td></tr>
<tr><td>Tick Delay</td><td>unsigned int</td></tr>
<tr><td>Should execute on first tick?</td><td>bool</td></tr>
</tbody></table>