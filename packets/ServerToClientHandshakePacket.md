# ServerToClientHandshakePacket

**ID: 3**  
**Purpose: Server->Client Handshake**  

Sent from the server at the end of the login packet

<table><thead><tr><th>Field</th><th>Info</th></tr></thead><tbody>
<tr><td>Handshake WebToken</td><td><table><tbody><tr><td>string</td><td>Base64 encoded JSON Web Token that contains the other relevant client properties.
  
  Properties Include:
  
  'salt' = (for use in encryption)
  
  The public key used to compute the shared secret for encryption is embedded in the header of the token. It's the signer public key (json value of 'x5u')</td></tr></tbody></table></td></tr>
</tbody></table>