# ClientboundMapItemDataPacket

__ID: 67__

This is sent either if the user is creating a new map, if a map that exists cannot be found, or if the user is creating a locked copy of a map.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Map ID</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
<tr><td>Type Flags</td><td>unsigned varint</td></tr>
<tr><td>Dimension</td><td>byte</td></tr>
<tr><td>Is Locked Map?</td><td>bool</td></tr>
<tr><td>Map Origin</td><td><a href="../types/BlockPos.md">BlockPos</a></td></tr>
<tr><td>Dependency on 'Creation Bit Field'</td><td><b>if (8)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Map ID List</td><td><b>Array Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Map ID entry</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
    <tr><td>Map ID entry</td><td><a href="../types/ActorUniqueID.md">ActorUniqueID</a></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Dependency on 'DecorationUpdate, TextureUpdate, or Creation Bit Field'</td><td><b>if (2)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Scale</td><td>byte</td></tr>
  </tbody></table><hr>
  <b>if (4)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Scale</td><td>byte</td></tr>
  </tbody></table><hr>
  <b>if (8)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Scale</td><td>byte</td></tr>
  </tbody></table></td></tr>
<tr><td>Dependency on 'DecorationUpdate Bit Field'</td><td><b>if (4)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Actor IDs</td><td><b>Array Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>MapItemTrackedActor ID</td><td><a href="../types/MapItemTrackedActor_UniqueId.md">MapItemTrackedActor::UniqueId</a></td></tr>
    </tbody></table></td></tr>
  <tr><td>Decoration List</td><td><b>Array Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Map Decoration</td><td><a href="../types/MapDecoration.md">MapDecoration</a></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
<tr><td>Dependency on 'TextureUpdate Bit Field'</td><td><b>if (2)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Texture Width</td><td>varint</td></tr>
  <tr><td>Texture Height</td><td>varint</td></tr>
  <tr><td>X-TexCoordinate</td><td>varint</td></tr>
  <tr><td>Y-TexCoordinate</td><td>varint</td></tr>
  <tr><td>Pixels</td><td><b>Array Size:</b> unsigned varint
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Pixel</td><td>unsigned varint</td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>