# ShapelessChemistryRecipe

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Recipe Id</td><td>string</td></tr>
<tr><td>Ingredients</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Entry</td><td><a href="../types/RecipeIngredient.md">RecipeIngredient</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Results</td><td><b>List Size:</b> unsigned varint
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Entry</td><td><a href="../types/NetworkItemInstanceDescriptor.md">NetworkItemInstanceDescriptor</a></td></tr>
  </tbody></table></td></tr>
<tr><td>Id</td><td><a href="../types/mce_UUID.md">mce::UUID</a></td></tr>
<tr><td>Tag</td><td><table><tbody><tr><td>string</td><td>As string</td></tr></tbody></table></td></tr>
<tr><td>Priority</td><td>varint</td></tr>
</tbody></table>