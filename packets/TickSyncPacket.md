# TickSyncPacket

__ID: 23__

Helps ensure client and server ticks are in sync.This packet is used to maintain a synchronized, server-authoritative tick between the client and the server

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Client Request Timestamp</td><td>int64</td></tr>
<tr><td>Server Reception Response Timestamp</td><td>int64</td></tr>
</tbody></table>