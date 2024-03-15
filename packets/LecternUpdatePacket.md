# LecternUpdatePacket

__ID: 125__

This is used for the Lectern Block Actor. It is a request from the client to either turn the page in the lectern or drop the book.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>New page to show</td><td>byte</td></tr>
<tr><td>Total Pages</td><td>byte</td></tr>
<tr><td>Position of Lectern to update</td><td><a href="../types/NetworkBlockPosition.md">NetworkBlockPosition</a></td></tr>
</tbody></table>