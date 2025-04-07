# UserDataShapelessRecipe

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Recipe Unique Id</td><td>string</td></tr>
<tr><td>Ingredient List</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Ingredient</td><td><a href="../types/RecipeIngredient.md">RecipeIngredient</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Production List</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Produced Item</td><td><a href="../types/NetworkItemInstanceDescriptor.md">NetworkItemInstanceDescriptor</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Recipe ID</td><td><a href="../types/mce_UUID.md">mce::UUID</a></td></tr>
<tr><td>Recipe Tag</td><td>string</td></tr>
<tr><td>Priority</td><td>varint</td></tr>
<tr><td>Unlocking Requirement</td><td><a href="../types/RecipeUnlockingRequirement.md">RecipeUnlockingRequirement</a></td></tr>
</tbody></table>