
SAML Bearer. 
* This flow uses SAML to authenticate on behalf of an user from one system to other system.
* The client system on behalf of the user creates a saml assertion and sends it to the authentication server. (Note: the assertion message should be base64 encoded)
* The authentication server validates the assertion and issues an access token.
* The client system then uses the access token to perform operations to the resource server.
* * No need for a connected app (when compared to other flows like JWT  or client credentials). It uses single sign on configuration
  
