# SetScoreboardIdentityPacket

**ID: 112**  
**Purpose: Set Scoreboard Identity**  

Send an update packet for a player identity definition iff a tracked player has logged in with a different display name.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Scoreboard Identity Packet Type</td><td>byte</td></tr>
<tr><td>Scoreboard Identity Info</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Scoreboard Id</td><td><a href="../types/ScoreboardId.md">ScoreboardId</a></td></tr>
  <tr><td>Dependency on 'Is Update Type'</td><td><b>If True</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Player Unique Id</td><td>varint64</td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>