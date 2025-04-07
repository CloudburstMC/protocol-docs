# PlayerFogPacket

__ID: 160__

This is the packet that tracks the active fog stack from the server so the local players can apply different fog settings.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Fog Stack</td><td><b>List Size:</b> unsigned varint
  Stack of fog effects created by /fog command  
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Fog Effect</td><td><table><tbody><tr><td>string</td><td>Fog effect string from /fog command</td></tr></tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>