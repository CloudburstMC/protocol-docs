# InventoryTransactionPacket

**ID: 30**  
**Purpose: Inventory Transaction**  

Sent for item interaction UI depending on if ItemStackNetManager is enabled as well as when the player uses items in gameplay. See ComplexInventoryTransaction::Type for more details

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Raw Id (32 bit signed)</td><td>varint</td></tr>
<tr><td>Dependency on 'Above ID (the legacy request ID) nonzero'</td><td><b>If True</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Legacy Set Item Slots</td><td><b>List Size:</b> unsigned varint
    Only matters when ItemStackNetManager is enabled  
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Container Enum</td><td>byte</td></tr>
    <tr><td>Slot vector</td><td><b>List Size:</b> unsigned varint
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Slot</td><td>byte</td></tr>
      </tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Transaction Type</td><td>unsigned varint</td></tr>
<tr><td>mTransaction->mTransaction</td><td><a href="../types/InventoryTransaction.md">InventoryTransaction</a></td></tr>
</tbody></table>