# SetTitlePacket

__ID: 88__

Used by 3rd party content for the purpose of showing ui banners. There are 2 commands associated with it: title and titleraw.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Title Type</td><td><table><tbody><tr><td>varint</td><td><a href="../enums/SetTitlePacket_TitleType.md">SetTitlePacket::TitleType</a></td></tr></tbody></table></td></tr>
<tr><td>Title Text</td><td>string</td></tr>
<tr><td>Fade In Time</td><td>varint</td></tr>
<tr><td>Stay Time</td><td>varint</td></tr>
<tr><td>Fade Out Time</td><td>varint</td></tr>
<tr><td>Xuid</td><td>string</td></tr>
<tr><td>Platform Online Id</td><td>string</td></tr>
</tbody></table>