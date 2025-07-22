# CreativeContentPacket

**ID: 145**  
**Purpose: Sent once by the server on startup to tell clients all of the items that can show up in the creative menu and recipe book.**  

This packet contains two lists, one for all the groups and one for all the items. Groups can either have an icon with a name, or can be loose groups of items that don't have a name (anonymous groups). All items need a group to represent them. Groups will show up in each category based on the order they are provided in the list. Items will show up in the order that they are represented in this packet. Each item needs to reference the index of a group from the list of groups.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Dependency on 'mCreativeItemRegistryForWrite != nullptr'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Groups</td><td><b>List Size:</b> unsigned varint
    This is a collection of all groups with and without names. Groups with names show up in the Creative Inventory/Recipe Book with a collapsible icon.  
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Creative Category</td><td>int</td></tr>
    <tr><td>Name of the group</td><td><table><tbody><tr><td>string</td><td>This is localized. Leave empty for an anonymous group (group that doesn't collapse).</td></tr></tbody></table></td></tr>
    <tr><td>Group Icon Item</td><td><a href="../types/NetworkItemInstanceDescriptor.md">NetworkItemInstanceDescriptor</a></td></tr>
    </tbody></table></td></tr>
  <tr><td>Write Entries</td><td><b>List Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Creative Net Id</td><td><a href="../types/TypedServerNetId_CreativeItemNetIdTag.md">TypedServerNetId&lt;struct CreativeItemNetIdTag,unsigned int,0&gt;</a></td></tr>
    <tr><td>Item Instance</td><td><a href="../types/NetworkItemInstanceDescriptor.md">NetworkItemInstanceDescriptor</a></td></tr>
    <tr><td>Group Index</td><td><table><tbody><tr><td>unsigned varint</td><td>Group Index referring to the group in the list `Groups`.</td></tr></tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>