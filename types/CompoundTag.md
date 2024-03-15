# CompoundTag

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Tag Type</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/Tag_Type.md">Tag::Type</a></td></tr></tbody></table></td></tr>
<tr><td>Dependency on 'if 'Tag Type' is 0'</td><td><b>if (0)</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Tag Name</td><td>string</td></tr>
  <tr><td>Dependency on 'Tag Type'</td><td><b>if (1)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>byte</td></tr>
    </tbody></table><hr>
    <b>if (2)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>short</td></tr>
    </tbody></table><hr>
    <b>if (3)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>varint</td></tr>
    </tbody></table><hr>
    <b>if (4)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>varint64</td></tr>
    </tbody></table><hr>
    <b>if (5)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>float</td></tr>
    </tbody></table><hr>
    <b>if (6)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>double</td></tr>
    </tbody></table><hr>
    <b>if (7)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Byte Array</td><td><b>Array Size:</b> varint
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Byte Data</td><td>byte</td></tr>
      </tbody></table></td></tr>
    </tbody></table><hr>
    <b>if (8)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>string</td></tr>
    </tbody></table><hr>
    <b>if (9)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Dependency on 'if empty list'</td><td><b>if (0)</b><br>
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Tag Type for list</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/Tag_Type.md">Tag::Type</a></td></tr></tbody></table></td></tr>
      </tbody></table><hr>
      <b>if (1)</b><br>
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Tag Type (must be 1)</td><td><table><tbody><tr><td>byte</td><td><a href="../enums/Tag_Type.md">Tag::Type</a></td></tr></tbody></table></td></tr>
      </tbody></table></td></tr>
    <tr><td>Tag Array</td><td><b>Array Size:</b> varint
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Tag (Recursive)</td><td><a href="../types/CompoundTag.md">CompoundTag</a></td></tr>
      </tbody></table></td></tr>
    </tbody></table><hr>
    <b>if (10)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Array</td><td><table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Tag (Recursive)</td><td><a href="../types/CompoundTag.md">CompoundTag</a></td></tr>
      </tbody></table></td></tr>
    <tr><td>End (must be 0)</td><td>byte</td></tr>
    </tbody></table><hr>
    <b>if (11)</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Int Array</td><td><b>Array Size:</b> varint
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Int Data</td><td>varint</td></tr>
      </tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>