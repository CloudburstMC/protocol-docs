# SubChunkPacket

**ID: 174**  
**Purpose: SubChunkPacket**  

Sent from server to client representing a batch of subchunk data and the required information to place the subchunk in the correct part of the world

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Cache Enabled</td><td>bool</td></tr>
<tr><td>Dimension Type</td><td>varint</td></tr>
<tr><td>Center Pos</td><td><a href="../types/SubChunkPos.md">SubChunkPos</a></td></tr>
<tr><td>SubChunk Data List</td><td><b>SubChunk Pos Offsets Size:</b> unsigned int
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>SubChunk Pos Offset</td><td><a href="../types/SubChunkPacket_SubChunkPosOffset.md">SubChunkPacket::SubChunkPosOffset</a></td></tr>
  <tr><td>SubChunk Request Result</td><td>byte</td></tr>
  <tr><td>Dependency on 'Cache Disabled or SubChunk Request Result SuccessAllAir?'</td><td><b>If True</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Serialized Sub Chunk</td><td>string</td></tr>
    </tbody></table></td></tr>
  <tr><td>Height Map Data Type</td><td>byte</td></tr>
  <tr><td>Dependency on 'Height Map Has Data'</td><td><b>If True</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Subchunk Height Map[0][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[0][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[1][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[2][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[3][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[4][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[5][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[6][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[7][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[8][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[9][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[10][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[11][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[12][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[13][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[14][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Height Map[15][15]</td><td>byte</td></tr>
    </tbody></table></td></tr>
  <tr><td>Render Height Map Data Type</td><td>byte</td></tr>
  <tr><td>Dependency on 'Render Height Map Has Data'</td><td><b>If True</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Subchunk Render Height Map[0][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[0][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[1][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[2][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[3][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[4][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[5][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[6][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[7][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[8][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[9][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[10][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[11][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[12][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[13][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[14][15]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][0]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][1]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][2]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][3]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][4]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][5]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][6]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][7]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][8]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][9]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][10]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][11]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][12]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][13]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][14]</td><td>byte</td></tr>
    <tr><td>Subchunk Render Height Map[15][15]</td><td>byte</td></tr>
    </tbody></table></td></tr>
  <tr><td>Dependency on 'Cache Enabled'</td><td><b>If True</b><br>
    <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
    <tr><td>Blob Id</td><td>unsigned int64</td></tr>
    </tbody></table></td></tr>
  </tbody></table></td></tr>
</tbody></table>