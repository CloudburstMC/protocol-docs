# UpdateAttributesPacket

__ID: 29__

Occasionally updating player attributes (buffs/debuffs, health, etc)

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Target Runtime ID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Attribute List</td><td><b>Array Size:</b> unsigned varint
  AttributeData - Helper Struct  
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Min Value</td><td>float</td></tr>
  <tr><td>Max Value</td><td>float</td></tr>
  <tr><td>Current Value</td><td>float</td></tr>
  <tr><td>Default Value</td><td>float</td></tr>
  <tr><td>Attribute Name</td><td>string</td></tr>
  <tr><td>Attribute Modifier</td><td><b>Array Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>ID</td><td>string</td></tr>
    <tr><td>Name</td><td>string</td></tr>
    <tr><td>Amount</td><td>float</td></tr>
    <tr><td>Operation</td><td><table><tbody><tr><td>int</td><td><a href="../enums/AttributeModifierOperation.md">AttributeModifierOperation</a></td></tr></tbody></table></td></tr>
    <tr><td>Operand</td><td><table><tbody><tr><td>int</td><td><a href="../enums/AttributeOperands.md">AttributeOperands</a></td></tr></tbody></table></td></tr>
    <tr><td>isSerializable?</td><td>bool</td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Count of ticks since simulation started</td><td>unsigned varint64</td></tr>
</tbody></table>