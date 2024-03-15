# SetHudPacket

__ID: 308__

This packet is only used via the set hud command. This is for 3rd party content.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Hud Element List</td><td><b>Array Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Hud Element</td><td><table><tbody><tr><td>varint</td><td><a href="../enums/HudElement.md">HudElement</a></td></tr></tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>isHudVisible</td><td><table><tbody><tr><td>varint</td><td><a href="../enums/HudVisibility.md">HudVisibility</a></td></tr></tbody></table></td></tr>
</tbody></table>