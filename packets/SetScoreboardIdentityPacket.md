# SetScoreboardIdentityPacket

__ID: 112__

Send an update packet for a player identity definition iff a tracked player has logged in with a different display name.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Scoreboard Identity Packet Type</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/ScoreboardIdentityPacketType.md">ScoreboardIdentityPacketType</a></td></tr></tbody></table></td></tr>
<tr><td>Identity Info</td><td><b>Array Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Scoreboard Id</td><td><a href="../types/ScoreboardId.md">ScoreboardId</a></td></tr>
  <tr><td>Dependency on 'Is Update Type'</td><td><b>if (1)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Player Unique Id</td><td>varint64</td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>