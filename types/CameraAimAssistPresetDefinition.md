# CameraAimAssistPresetDefinition

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>identifier</td><td><table><tbody><tr><td>identifier</td><td>Namespaced identifier for Camera Aim-Assist preset. Namespace and name must be separated by a ':'.</td></tr></tbody></table></td></tr>
<tr><td>exclusion_list</td><td><table><tbody><tr><td>List Size</td><td>Optional. List of block/entity identifiers to exclude from aim assist targeting.</td></tr></tbody></table></td></tr>
<tr><td>liquid_targeting_list</td><td><table><tbody><tr><td>List Size</td><td>Optional. List of item identifiers that will target liquid blocks with aim-assist when being held.</td></tr></tbody></table></td></tr>
<tr><td>item_settings</td><td><table><tbody><tr><td>map<Reference,Reference></td><td>Optional. Map of Item identifiers to Aim-Assist Category names found in the specified 'categories'.</td></tr></tbody></table></td></tr>
<tr><td>default_item_settings</td><td><table><tbody><tr><td>default_item_settings</td><td>Optional. Default Aim-Assist Category used for Items not found in 'item_settings'.</td></tr></tbody></table></td></tr>
<tr><td>hand_settings</td><td><table><tbody><tr><td>hand_settings</td><td>Optional. Aim-assist Category used for an empty hand.</td></tr></tbody></table></td></tr>
</tbody></table>