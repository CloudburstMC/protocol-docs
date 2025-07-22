# ItemStackRequestPacket

**ID: 147**  
**Purpose: ItemStackRequestPacket**  

The new server auth inventory item transaction request. This is done in batches of items, and is as of Dec 2019

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Requests</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Client Request Id</td><td><a href="../types/TypedClientNetId_ItemStackRequestIdTag.md">TypedClientNetId&lt;struct ItemStackRequestIdTag,int,0&gt;</a></td></tr>
  <tr><td>Actions</td><td><b>List Size:</b> unsigned varint
    There are a variety of possible actions each with their own schema; this (Take) is just one example. Refer to the Item Stack Net Manager documentation.  
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Action type</td><td>byte</td></tr>
    <tr><td>Amount</td><td>byte</td></tr>
    <tr><td>Source</td><td><a href="../types/ItemStackRequestSlotInfo.md">ItemStackRequestSlotInfo</a></td></tr>
    <tr><td>Destination</td><td><a href="../types/ItemStackRequestSlotInfo.md">ItemStackRequestSlotInfo</a></td></tr>
    </tbody></table></td></tr>
  <tr><td>Strings To Filter</td><td><b>List Size:</b> unsigned varint
    Array of strings to submit to profanity filtering service  
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>String To Filter</td><td><table><tbody><tr><td>string</td><td>Indivdiual string that needs checking</td></tr></tbody></table></td></tr>
    </tbody></table></td></tr>
  <tr><td>StringsToFilterOrigin</td><td>int</td></tr>
  </tbody></table></td></tr>
</tbody></table>