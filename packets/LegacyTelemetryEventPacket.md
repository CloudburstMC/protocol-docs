# LegacyTelemetryEventPacket

__ID: 65__

This is a legacy packet and should not be used anymore, although server side telemetry is not widely used/tested yet.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Actor ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Event Type</td><td>varint</td></tr>
<tr><td>Use Player ID</td><td>byte</td></tr>
<tr><td>Dependency on 'Event Type'</td><td><b>if (0)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Achievement ID</td><td>varint</td></tr>
  </tbody></table><hr>
  <b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Interacted Entity ID</td><td>varint64</td></tr>
  <tr><td>Interaction Type</td><td>varint</td></tr>
  <tr><td>Interaction Actor Type</td><td>varint</td></tr>
  <tr><td>Interaction Actor Variant</td><td>varint</td></tr>
  <tr><td>Interaction Actor Color</td><td>byte</td></tr>
  </tbody></table><hr>
  <b>if (2)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Dimension ID</td><td>varint</td></tr>
  </tbody></table><hr>
  <b>if (3)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Source Dimension ID</td><td>varint</td></tr>
  <tr><td>Target Dimension ID</td><td>varint</td></tr>
  </tbody></table><hr>
  <b>if (4)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Instigator Actor ID</td><td>varint64</td></tr>
  <tr><td>Target Actor ID</td><td>varint64</td></tr>
  <tr><td>Instigator's Child Actor Type</td><td>varint</td></tr>
  <tr><td>Damage Source</td><td>varint</td></tr>
  <tr><td>Trade Tier</td><td><table><tbody><tr><td>varint</td><td>-1 if not a trading actor.</td></tr></tbody></table></td></tr>
  <tr><td>Trader Name</td><td><table><tbody><tr><td>string</td><td>Empty if not a trading actor.</td></tr></tbody></table></td></tr>
  </tbody></table><hr>
  <b>if (5)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Contents Color</td><td>unsigned varint</td></tr>
  <tr><td>Contents Type</td><td>varint</td></tr>
  <tr><td>Fill Level</td><td>varint</td></tr>
  </tbody></table><hr>
  <b>if (6)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Instigator Actor ID</td><td>varint</td></tr>
  <tr><td>Instigator Mob Variant</td><td>varint</td></tr>
  <tr><td>Damage Source</td><td>varint</td></tr>
  <tr><td>Died in Raid?</td><td>bool</td></tr>
  </tbody></table><hr>
  <b>if (7)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Boss Actor ID</td><td>varint64</td></tr>
  <tr><td>Party Size</td><td>varint</td></tr>
  <tr><td>Boss Type</td><td>varint</td></tr>
  </tbody></table><hr>
  <b>if (8)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Result</td><td>varint</td></tr>
  <tr><td>Result Number</td><td>varint</td></tr>
  <tr><td>Command Name</td><td>string</td></tr>
  <tr><td>Result Key</td><td>string</td></tr>
  <tr><td>Result String</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (11)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Success Count</td><td>varint</td></tr>
  <tr><td>Error Count</td><td>varint</td></tr>
  <tr><td>Command Name</td><td>string</td></tr>
  <tr><td>Error List</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (13)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Born Baby: Entity Type</td><td>varint</td></tr>
  <tr><td>Born Baby: Entity Variant</td><td>varint</td></tr>
  <tr><td>Born Baby: Color</td><td>byte</td></tr>
  </tbody></table><hr>
  <b>if (15)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Block Interaction Type</td><td>varint</td></tr>
  <tr><td>Item Id</td><td><table><tbody><tr><td>varint</td><td>Id of the relevant item used in the interaction.</td></tr></tbody></table></td></tr>
  </tbody></table><hr>
  <b>if (16)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Block Interaction Type</td><td>varint</td></tr>
  <tr><td>Item Id</td><td><table><tbody><tr><td>varint</td><td>Id of the relevant item used in the interaction.</td></tr></tbody></table></td></tr>
  </tbody></table><hr>
  <b>if (17)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Item Id</td><td><table><tbody><tr><td>varint</td><td>Id of the relevant item used in the interaction.</td></tr></tbody></table></td></tr>
  </tbody></table><hr>
  <b>if (18)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Event Name</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (19)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Current Raid Wave</td><td>varint</td></tr>
  <tr><td>Total Raid Waves</td><td>varint</td></tr>
  <tr><td>Won Raid</td><td>bool</td></tr>
  </tbody></table><hr>
  <b>if (23)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Redstone Level</td><td>varint</td></tr>
  </tbody></table><hr>
  <b>if (24)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Item Id</td><td>varint</td></tr>
  <tr><td>Was targeting bartering player</td><td>bool</td></tr>
  </tbody></table><hr>
  <b>if (25)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Player Waxed or Unwaxed Copper Block ID</td><td>varint</td></tr>
  </tbody></table><hr>
  <b>if (26)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Code builder runtime action</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (27)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Objective Name</td><td>string</td></tr>
  <tr><td>Code Builder Scoreboard Score</td><td>varint</td></tr>
  </tbody></table></td></tr>
</tbody></table>