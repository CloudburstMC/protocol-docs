# ConnectionRequest

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Certificate Chain (JSON)</td><td><b>Array Size:</b> int
  Array of Base64 encoded JSON Web Token certificates to authenticate the player.
  
  The last certificate in the chain will have a property 'extraData' that contains player identity information including the XBL XUID (if the player was signed into XBL at the time of the connection).  
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>String Data</td><td>byte</td></tr>
  </tbody></table></td></tr>
<tr><td>Raw Token</td><td><b>Array Size:</b> int
  Base64 encoded JSON Web Token that contains other relevant client properties."
  				"Properties Include:
  				'SelfSignedId'
  				'ServerAddress' = (unresolved url if applicable)
  				'ClientRandomId'
  				'SkinId'
  				'SkinData'
  				'SkinImageWidth'
  				'SkinImageHeight'
  				'CapeData'
  				'CapeImageWidth'
  				'CapeImageHeight'
  				'SkinResourcePatch'
  				'SkinGeometryData'
  				'SkinGeometryDataEngineVersion'
  				'SkinAnimationData'
  				'PlayFabId'
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
  				'IsEduMode (if edu mode)'
  				'TenantId (if edu mode)'
  				'ADRole (if edu mode)'
  				'IsEditorMode'
  				'GameVersion'
  				'DeviceModel'
  				'DeviceOS' = (see enumeration: BuildPlatform)
  				'DefaultInputMode' = (see enumeration: InputMode)
  				'CurrentInputMode' = (see enumeration: InputMode)
  				'UIProfile' = (see enumeration: UIProfile)
  				'GuiScale'
  				'LanguageCode'
  				'PlatformUserId'
  				'ThirdPartyName'
  				'PlatformOnlineId'
  				'PlatformOfflineId'
  				'DeviceId'
  				'TrustedSkin'
  				'PremiumSkin'
  				'PersonaSkin'
  				'OverrideSkin'
  				'CapeOnClassicSkin'
  				'CapeId'
  				'CompatibleWithClientSideChunkGen'  
  <table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
  <tr><td>String Data</td><td>byte</td></tr>
  </tbody></table></td></tr>
</tbody></table>