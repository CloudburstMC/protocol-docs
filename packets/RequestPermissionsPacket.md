# RequestPermissionsPacket

**ID: 185**  
**Purpose: RequestPermissionsPacket**  

Sent from client to server. Used to request a new Permissions Levels. Can only be used by Operators or Hosts.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Player Id's Raw ID</td><td><table><tbody><tr><td>int64</td><td>mTargetPlayerId is a ActorUniqueID</td></tr></tbody></table></td></tr>
<tr><td>Player Permission Level</td><td>varint</td></tr>
<tr><td>Custom Permission Flags</td><td>unsigned short</td></tr>
</tbody></table>