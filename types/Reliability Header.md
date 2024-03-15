# Reliability Header

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Reliability Type (3 bits), is packet split? (1 bit)</td><td>byte</td></tr>
<tr><td>Payload Bit Length</td><td>unsigned short</td></tr>
<tr><td>Dependency on 'Reliability Type'</td><td><b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Sequenced Index</td><td>unsigned int24</td></tr>
  <tr><td>Ordering Index</td><td>unsigned int24</td></tr>
  <tr><td>Ordering Channel</td><td>byte</td></tr>
  </tbody></table><hr>
  <b>if (2)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Reliable Message</td><td>unsigned int24</td></tr>
  </tbody></table><hr>
  <b>if (3)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Reliable Message</td><td>unsigned int24</td></tr>
  <tr><td>Ordering Index</td><td>unsigned int24</td></tr>
  <tr><td>Ordering Channel</td><td>byte</td></tr>
  </tbody></table><hr>
  <b>if (4)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Reliable Message</td><td>unsigned int24</td></tr>
  <tr><td>Sequenced Index</td><td>unsigned int24</td></tr>
  <tr><td>Ordering Index</td><td>unsigned int24</td></tr>
  <tr><td>Ordering Channel</td><td>byte</td></tr>
  </tbody></table></td></tr>
<tr><td>Dependency on 'Is Packet Split?'</td><td><b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Split Packet Count</td><td>unsigned int</td></tr>
  <tr><td>Split Packet Id</td><td>unsigned short</td></tr>
  <tr><td>Split Packet Index</td><td>unsigned int</td></tr>
  </tbody></table></td></tr>
</tbody></table>