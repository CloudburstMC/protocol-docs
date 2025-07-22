# SetTitlePacket

**ID: 88**  
**Purpose: Used by 3rd party content for the purpose of showing ui banners**  

There are 2 commands associated with it: title and titleraw. Both of which have functionality to change fade in/out time for titles, sub titles, and action bar text.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Title Type</td><td>enum SetTitlePacket TitleType</td></tr>
<tr><td>Title Text</td><td>string</td></tr>
<tr><td>Fade In Time</td><td>varint</td></tr>
<tr><td>Stay Time</td><td>varint</td></tr>
<tr><td>Fade Out Time</td><td>varint</td></tr>
<tr><td>Xuid</td><td>string</td></tr>
<tr><td>Platform Online Id</td><td>string</td></tr>
<tr><td>Filtered Title Message</td><td>string</td></tr>
</tbody></table>