# ModalFormResponsePacket

__ID: 101__

Fired in response to third party server request to show the custom UI screen.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Form ID</td><td>unsigned varint</td></tr>
<tr><td>JSON Response</td><td><a href="../types/Optional_class Json_Value.md">std::optional<class Json::Value></a></td></tr>
<tr><td>Form Cancel Reason</td><td><a href="../types/Optional_enum ModalFormCancelReason.md">std::optional<enum ModalFormCancelReason></a></td></tr>
</tbody></table>