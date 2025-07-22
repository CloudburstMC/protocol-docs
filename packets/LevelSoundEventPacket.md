# LevelSoundEventPacket

**ID: 123**  
**Purpose: Level Sound Event**  

Most sounds get launched on server and replicated to clients, but a handful of player initiated sounds are launched on their client and replicated through the network. (In most of the codebase 'Event' means telemetry events; this is not the case here, this is how sounds get replicated across the network in vanilla.) With support for custom entities. Entity Id is a string and Event Id is an integer.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Event ID</td><td>enum LevelSoundEvent</td></tr>
<tr><td>Position</td><td>X</td></tr>
<tr><td>Data</td><td>varint</td></tr>
<tr><td>Actor Identifier</td><td>string</td></tr>
<tr><td>Is Baby</td><td>bool</td></tr>
<tr><td>Is Global</td><td>bool</td></tr>
<tr><td>Actor Unique Id</td><td>int64</td></tr>
</tbody></table>