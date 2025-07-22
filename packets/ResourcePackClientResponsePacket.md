# ResourcePackClientResponsePacket

**ID: 8**  
**Purpose: Resource Pack Client Response**  

Sent to MinecraftGame to complete the resource pack loading process.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Response</td><td>byte</td></tr>
<tr><td>Downloading Packs Size</td><td>unsigned short</td></tr>
<tr><td>Dependency on 'Downloading Packs'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Downloading Packs</td><td><table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Pack Name</td><td>string</td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>