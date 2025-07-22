# CameraShakePacket

**ID: 159**  
**Purpose: Used to control trigger camera shake movements on the client's player camera**  

It may be used to queue or stop a camera shake

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Intensity</td><td><table><tbody><tr><td>float</td><td>Camera shake intensity</td></tr></tbody></table></td></tr>
<tr><td>Seconds</td><td><table><tbody><tr><td>float</td><td>Camera shake duration in seconds</td></tr></tbody></table></td></tr>
<tr><td>Shake Type</td><td><table><tbody><tr><td>enum CameraShakeType</td><td>The type of calculation used for determining camera shake</td></tr></tbody></table></td></tr>
<tr><td>Shake Action</td><td><table><tbody><tr><td>enum CameraShakeAction</td><td>The action to perform to camera shake</td></tr></tbody></table></td></tr>
</tbody></table>