# Authentication

+ What is OAuth? 

 OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.


+ Give an example of what using OAuth would look like.

When we wish to connect on to a new account with a different account exactly like we check on on GitHub to Netlify


+ How does OAuth work? What are the steps that it takes to authenticate the user?

 when you request a service, maybe it will have many services inside it.
you have to access your data as a user on one website.
after this logon, every service from a different website will access your authorization by OAuth.
finally, you will receive the response for all services that you were sending requests for them.


+ What is OpenID?

it is something like OAuth, but OpenID related to authentication, not like OAuth that is related to authorization.
also, OpenID is accessing data from user to machine, but OAuth is accessing data from machine to machine on behalf of the user.


+ What is the difference between authorization and authentication?


Authentication is the act of validating that users are whom they claim to be. This is the first step in any security process. Authorization in system security is the process of giving the user permission to access a specific resource or function. This term is often used interchangeably with access control or client privilege


+ What is Authorization Code Flow?

Because regular web apps are server-side apps where the source code is not publicly exposed, they can use the Authorization Code Flow, which exchanges an Authorization Code for a token.


+ What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

During authentication, mobile and native applications can use the Authorization Code Flow, but they require additional security. Additionally, single-page apps have special challenges. To mitigate these, OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE).

+ What is Implicit Flow with Form Post?


As an alternative to the Authorization Code Flow, OAuth 2.0 provides the Implicit Flow, which is intended for Public Clients, or applications which are unable to securely store Client Secrets

+ What is Client Credentials Flow?

Client Credentials Flow pass along their Client ID and Client Secret to authenticate themselves and get a token.


+ What is Device Authorization Flow?

With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device. This avoids a poor user experience for devices that do not have an easy way to enter text. To do this, device apps use the Device Authorization Flow (drafted in OAuth 2.0). For use with mobile/native applications.

