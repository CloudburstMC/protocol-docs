# ModalFormRequestPacket

**ID: 100**  
**Purpose: Modal Form Request**  

Not sent from vanilla. The feature is meant for third-party servers to be able to drive dynamic ui forms. The request comes with some JSON that describes a custom UI screen thirdparty uses.Server->client.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Form ID</td><td>unsigned varint</td></tr>
<tr><td>Form UI JSON</td><td>string</td></tr>
</tbody></table>