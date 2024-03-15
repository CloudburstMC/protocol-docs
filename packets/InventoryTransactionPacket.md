# InventoryTransactionPacket

__ID: 30__



<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Raw Id (32 bit signed)</td><td>varint</td></tr>
<tr><td>Dependency on 'above ID (the legacy request ID) nonzero'</td><td><b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Legacy Set Item Slots</td><td><b>Array Size:</b> unsigned varint
    Only matters when ItemStackNetManager is enabled  
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Container Enum</td><td>byte</td></tr>
    <tr><td>Slot vector</td><td><b>Array Size:</b> unsigned varint
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Slot</td><td>byte</td></tr>
      </tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Transaction Type</td><td><table><tbody><tr><td>unsigned varint</td><td><a href="../enums/ComplexInventoryTransaction_Type.md">ComplexInventoryTransaction::Type</a></td></tr></tbody></table></td></tr>
<tr><td>mTransaction->mTransaction</td><td><a href="../types/InventoryTransaction.md">InventoryTransaction</a></td></tr>
</tbody></table>