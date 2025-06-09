# SubClientConnectionRequest

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Certificate Chain (JSON)</td><td><b>Array Size:</b> int
  Array of Base64 encoded JSON Web Token certificates to authenticate the player.The last certificate in the chain will have a property 'extraData' that contains player identity information including the XBL XUID (if the player was signed into XBL at the time of the connection).  
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>String Data</td><td>byte</td></tr>
  </tbody></table></td></tr>
<tr><td>Raw Token</td><td><b>Array Size:</b> int
  Base64 encoded JSON Web Token that contains other relevant client properties.
  				Properties Include:
  				'SelfSignedId'
  				'ClientRandomId'
  				'PlatformUserId'
  				'SkinId'
  				'SkinData'
  				'SkinImageWidth'
  				'SkinImageHeight'
  				'CapeData'
  				'CapeImageWidth'
  				'CapeImageHeight'
  				'SkinResources'
  				'SkinGeometry'
  				'SkinGeometryDataEngineVersion'
  				'SkinAnimationData'
  				'PlayFabId'
  				'DeviceId'
  				'TrustedSkin'
  				'PremiumSkin'
  				'PersonaSkin'
  				'AnimatedImageData = Array of:'
  				'-- Type'
  				'-- Image'
  				'-- ImageWidth'
  				'-- ImageHeight'
  				'-- Frames'
  				'-- AnimationExpression'
  				'ArmSize'
  				'SkinColor'
  				'PersonaPieces = Array of:'
  				'-- PackId'
  				'-- PieceId'
  				'-- IsDefault'
  				'-- PieceType'
  				'-- ProuctId'
  				'PieceTintColors = Array of:'
  				'-- PieceType'
  				'-- Colors = Array of color hexstrings'
  				'DefaultInputMode' = (see enumeration: InputMode)
  				'CurrentInputMode' = (see enumeration: InputMode)
  				'ThirdPartyName'
  				'PlatformOnlineId'
  				'PlatformOfflineId'
                  'DeviceOS' = (see enumeration: BuildPlatform)
  				'CapeOnClassicSkin'
  				'CapeId'
  				'PrimaryUser'
  				'CompatibleWithClientSideChunkGen'  
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>String Data</td><td>byte</td></tr>
  </tbody></table></td></tr>
</tbody></table>