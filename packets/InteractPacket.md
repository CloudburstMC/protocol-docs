# InteractPacket

**ID: 33**  
**Purpose: Interact**  

Used for inventory button press and in _updateInteraction() for a variety of purposes.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Action</td><td>byte</td></tr>
<tr><td>Target Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Dependency on 'Action == InteractUpdate || Action == StopRiding'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Position X</td><td>float</td></tr>
  <tr><td>Position Y</td><td>float</td></tr>
  <tr><td>Position Z</td><td>float</td></tr>
  </tbody></table></td></tr>
</tbody></table>