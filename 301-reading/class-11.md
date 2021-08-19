# Class Eleven

[Home](https://daviey52.github.io/reading-notes/)

1. What is OAuth?
OAuth is an open-standard authorization protocol that describes how unrelated servers and services can safely allows authenticated access to their assets without actually sharing the initial, related single logon credential.
2. Give an example of what using OAuth would look like.
Netlify authorizing you to using a GitHub account
3. How does OAuth work? What are the steps that it takes to authenticate the user?
  According to Roger A.Grimes et.al.(2019), the following are the steps on how OAuth works
• The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
• The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
• The first site gives this token and secret to the initiating user’s client software.
• The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
• If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
• The user approves (or their software silently approves) a particular transaction type at the first website.
• The user is given an approved access token (notice it’s no longer a request token).
• The user gives the approved access token to the first website.
• The first website gives the access token to the second website as proof of authentication on behalf of the user.
• The second website lets the first website access their site on behalf of the user.
• The user sees a successfully completed transaction occurring.
• OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).

• What is OpenID?
      OpenID is about authentication, and it is more for humans logging into machines

1. What is the difference between authorization and authentication?
  Authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to.
2. What is Authorization Code Flow?
Because regular web app are server-side apps where the source code is not publicly exposed, they can use the Authorization Code Flow, which exchanges an Authorization code for a token.
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
  PKE-enhanced Authorization Code Flow introduces a secrete by calling application that can be verified by the authorized server. This secrete is called the code verifier.
4. What is Implicit Flow with Form Post?
As an alternative to the Authorization Code flow, OAuth provides the implicit flow that is intended for Public Client, or applications that are unable to securely store Client Secret.
5. What is Client Credentials Flow?
With machine-to-machine application, such as CLIs, daemons, or service running on the backed-end, the system authenticates and authorizes the app rather than a user
6. What is Device Authorization Flow?
With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device.
7. What is Resource Owner Password Flow?

Reference

Roger A.Grimes , Josh Fruhlinger.(2019). What is Oauth? How the open authorization framework works. [OAuth] (<https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html>)

[Auth0](https://auth0.com/docs/libraries/auth0-react)
