# PlayerVideoCapturePacket

**ID: 324**  
**Purpose: Start/stops video capture for a player. Non-publish/test only.**  

internalInternal. Used by a test command to start/stop video capture. Non-publish/test only.

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Dependency on 'Action'</td><td><b>Start Video Capture</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Action</td><td>bool</td></tr>
  <tr><td>FrameRate</td><td>unsigned int</td></tr>
  <tr><td>FilePrefix</td><td>string</td></tr>
  </tbody></table><hr>
  <b>Stop Video Capture</b><br>
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>Action</td><td>bool</td></tr>
  </tbody></table></td></tr>
</tbody></table>