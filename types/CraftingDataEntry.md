# CraftingDataEntry

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Crafting Type</td><td>varint</td></tr>
<tr><td>Dependency on 'Crafting Type'</td><td><b>if (0)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Shapeless Recipe</td><td><a href="../types/ShapelessRecipe.md">ShapelessRecipe</a></td></tr>
  <tr><td>Net id</td><td><a href="../types/TypedServerNetId_RecipeNetIdTag.md">TypedServerNetId&lt;struct RecipeNetIdTag,unsigned int,0&gt;</a></td></tr>
  </tbody></table><hr>
  <b>if (1)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Shaped Recipe</td><td><a href="../types/ShapedRecipe.md">ShapedRecipe</a></td></tr>
  <tr><td>Net id</td><td><a href="../types/TypedServerNetId_RecipeNetIdTag.md">TypedServerNetId&lt;struct RecipeNetIdTag,unsigned int,0&gt;</a></td></tr>
  </tbody></table><hr>
  <b>if (2)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Item Data</td><td>varint</td></tr>
  <tr><td>Result Item</td><td><a href="../types/NetworkItemInstanceDescriptor.md">NetworkItemInstanceDescriptor</a></td></tr>
  <tr><td>Recipe Tag</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (3)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Item Data</td><td>varint</td></tr>
  <tr><td>Auxiliary Item Data</td><td>varint</td></tr>
  <tr><td>Result Item</td><td><a href="../types/NetworkItemInstanceDescriptor.md">NetworkItemInstanceDescriptor</a></td></tr>
  <tr><td>Recipe Tag</td><td>string</td></tr>
  </tbody></table><hr>
  <b>if (4)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Multi-Recipe</td><td><a href="../types/mce_UUID.md">mce::UUID</a></td></tr>
  <tr><td>Net id</td><td><a href="../types/TypedServerNetId_RecipeNetIdTag.md">TypedServerNetId&lt;struct RecipeNetIdTag,unsigned int,0&gt;</a></td></tr>
  </tbody></table><hr>
  <b>if (5)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>User Data Shapeless Recipe</td><td><a href="../types/UserDataShapelessRecipe.md">UserDataShapelessRecipe</a></td></tr>
  <tr><td>Net id</td><td><a href="../types/TypedServerNetId_RecipeNetIdTag.md">TypedServerNetId&lt;struct RecipeNetIdTag,unsigned int,0&gt;</a></td></tr>
  </tbody></table><hr>
  <b>if (6)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Shapeless Chemistry Recipe</td><td><a href="../types/ShapelessChemistryRecipe.md">ShapelessChemistryRecipe</a></td></tr>
  <tr><td>Net id</td><td><a href="../types/TypedServerNetId_RecipeNetIdTag.md">TypedServerNetId&lt;struct RecipeNetIdTag,unsigned int,0&gt;</a></td></tr>
  </tbody></table><hr>
  <b>if (7)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Shaped Chemistry Recipe</td><td><a href="../types/ShapedChemistryRecipe.md">ShapedChemistryRecipe</a></td></tr>
  <tr><td>Net id</td><td><a href="../types/TypedServerNetId_RecipeNetIdTag.md">TypedServerNetId&lt;struct RecipeNetIdTag,unsigned int,0&gt;</a></td></tr>
  </tbody></table><hr>
  <b>if (8)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Smithing Transform Recipe</td><td><a href="../types/SmithingTransformRecipe.md">SmithingTransformRecipe</a></td></tr>
  <tr><td>Net id</td><td><a href="../types/TypedServerNetId_RecipeNetIdTag.md">TypedServerNetId&lt;struct RecipeNetIdTag,unsigned int,0&gt;</a></td></tr>
  </tbody></table><hr>
  <b>if (9)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Smithing Trim Recipe</td><td><a href="../types/SmithingTrimRecipe.md">SmithingTrimRecipe</a></td></tr>
  <tr><td>Net id</td><td><a href="../types/TypedServerNetId_RecipeNetIdTag.md">TypedServerNetId&lt;struct RecipeNetIdTag,unsigned int,0&gt;</a></td></tr>
  </tbody></table></td></tr>
</tbody></table>