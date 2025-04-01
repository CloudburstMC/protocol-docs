# CompoundTag

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Tag Type</td><td>byte</td></tr>
<tr><td>Dependency on 'if 'Tag Type' is 0'</td><td><b>If False</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Tag Name</td><td>string</td></tr>
  <tr><td>Dependency on 'Tag Type'</td><td><b>Tag::Type::Byte</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>byte</td></tr>
    </tbody></table><hr>
    <b>Tag::Type::Short</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>short</td></tr>
    </tbody></table><hr>
    <b>Tag::Type::Int</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>varint</td></tr>
    </tbody></table><hr>
    <b>Tag::Type::Int64</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>varint64</td></tr>
    </tbody></table><hr>
    <b>Tag::Type::Float</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>float</td></tr>
    </tbody></table><hr>
    <b>Tag::Type::Double</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>double</td></tr>
    </tbody></table><hr>
    <b>Tag::Type::ByteArray</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Byte Array</td><td><b>Array Size:</b> varint
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Byte Data</td><td>byte</td></tr>
      </tbody></table></td></tr>
    </tbody></table><hr>
    <b>Tag::Type::String</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Value</td><td>string</td></tr>
    </tbody></table><hr>
    <b>Tag::Type::List</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Dependency on 'If Empty List'</td><td><b>If False</b><br>
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Tag Type for list</td><td>byte</td></tr>
      </tbody></table><hr>
      <b>If True</b><br>
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Tag Type (must be 1)</td><td>byte</td></tr>
      </tbody></table></td></tr>
    <tr><td>Tag Array</td><td><b>Array Size:</b> varint
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Tag (Recursive)</td><td><a href="../types/CompoundTag.md">CompoundTag</a></td></tr>
      </tbody></table></td></tr>
    </tbody></table><hr>
    <b>Tag::Type::Compound</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Tag Array</td><td><table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Tag (Recursive)</td><td><a href="../types/CompoundTag.md">CompoundTag</a></td></tr>
      </tbody></table></td></tr>
    <tr><td>End (must be 0)</td><td>byte</td></tr>
    </tbody></table><hr>
    <b>Tag::Type::IntArray</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Int Array</td><td><b>Array Size:</b> varint
      <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
      <tr><td>Int Data</td><td>varint</td></tr>
      </tbody></table></td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>