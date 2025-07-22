# UpdateAttributesPacket

**ID: 29**  
**Purpose: Update Attributes**  

Occasionally updating player attributes (buffs/debuffs, health, etc) The following attributes are important to supply with valid PlayerInputTick values for player movement simulation: - movement_speed - underwater_movement_speed - lava_movement_speed - jump_strength - hunger

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>RuntimeID</td><td><a href="../types/ActorRuntimeID.md">ActorRuntimeID</a></td></tr>
<tr><td>Attribute List</td><td><b>List Size:</b> unsigned varint
  AttributeData - Helper Struct  
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Min Value</td><td>float</td></tr>
  <tr><td>Max Value</td><td>float</td></tr>
  <tr><td>Current Value</td><td>float</td></tr>
  <tr><td>Default Min Value</td><td>float</td></tr>
  <tr><td>Default Max Value</td><td>float</td></tr>
  <tr><td>Default Value</td><td>float</td></tr>
  <tr><td>Name</td><td>string</td></tr>
  <tr><td>Modifiers</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Id</td><td>string</td></tr>
    <tr><td>Name</td><td>string</td></tr>
    <tr><td>Amount</td><td>float</td></tr>
    <tr><td>Operation</td><td>int</td></tr>
    <tr><td>Operand</td><td>int</td></tr>
    <tr><td>Is Serializable?</td><td>bool</td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Tick</td><td><a href="../types/PlayerInputTick.md">PlayerInputTick</a></td></tr>
</tbody></table>