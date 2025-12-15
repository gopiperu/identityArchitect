SAML Assertion flow: 

* This flow involves an Additional IDP system and a little bit more nuanced when it comes to setup.
* In this flow, the IDP system creates a SAML assertion and pass it to the client. the client then sends the assertion to the authentication server.(Note: the message should be base64 encoded and then url encoded)
* Once, the assertion is validated by the authentication server, it issues an access token.
* It appears that this flow is not ideal when it comes to security.
* No need for a connected app (when compared to other flows like JWT  or client credentials). It uses single sign on configuration

Almost Impractical: 
Why: Because it has some restrictions. 

Limitation: 
* Experience cloud doesnt support this flow
