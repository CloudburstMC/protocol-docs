# ContainerRegistryCleanupPacket

**ID: 317**  
**Purpose: This is used to trigger a clientside cleanup of the dynamic container registry.**  

Whenever the serverside ContainerRegistry does a clean, identifiers for the removed containers are gathered in a ContainerRegistryCleanUp packet and sent to the client so that the clientside container registry can remove those same containers.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Removed Containers</td><td>List Size</td></tr>
</tbody></table>