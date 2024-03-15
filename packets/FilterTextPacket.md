# FilterTextPacket

__ID: 163__

Client UIs use this packet to send strings for profanity filtering and the server returns them for preview strings

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Text</td><td>string</td></tr>
<tr><td>From Server</td><td><table><tbody><tr><td>bool</td><td>Whether this message is a filtered string from the server or a string in need of filtering from the client</td></tr></tbody></table></td></tr>
</tbody></table>