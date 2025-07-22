# PurchaseReceiptPacket

**ID: 92**  
**Purpose: Sent from client to server**  

Sent from the client after we make a purchase in the store OR if we login and our entitlements are verified. It sends a vector of purchase receipts(string).There is a handler and a multiple senders.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>PurchaseReceipts</td><td><table><tbody><tr><td>List Size</td><td>Purchase Receipts</td></tr></tbody></table></td></tr>
</tbody></table>