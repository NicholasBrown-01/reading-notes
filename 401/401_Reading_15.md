[BACK TO MAIN DIRECTORY](../README.md)

#### Reading Notes: 15
<br>

## What is OAuth

1. What is OAuth?
<br>
- Open Standard for Authorization for 3rd party apps to access resources.

2. Give an example of what using OAuth would look like.
<br>
- User logging in with a Google or Facebook account.

3. How does OAuth work? What are the steps that it takes to authenticate the user?
<br>
- It uses tokens and redirects to grant access:<br>
- - The third-party application redirects the user.
- -  User logs in to the authorization server and grants permission to the third-party app.
- -  An access token and another redirects for the user.
- - 3rd part app uses that access token to access the user's data.

4. What is OpenID?
<br>
- A single credential is used on multiple sites.

## Authorization and Authentication flows

1. What is the difference between authorization and authentication?
<br>
- Authentication verifies user identity, authorization grants of denies access or permission based on role. 

2. What is Authorization Code Flow?
<br>
[Auth0.com](https://auth0.com/docs/get-started/authentication-and-authorization-flow/authorization-code-flow)

>The user clicks Login within the regular web application.

>Auth0's SDK redirects the user to the Auth0 Authorization Server (
/authorize
endpoint).

>Your Auth0 Authorization Server redirects the user to the login and authorization prompt.

>The user authenticates using one of the configured login options and may see a consent page listing the permissions Auth0 will give to the regular web application.

>Your Auth0 Authorization Server redirects the user back to the application with an authorization code, which is good for one use.

>Auth0's SDK sends this code to the Auth0 Authorization Server (
/oauth/token
endpoint) along with the application's Client ID and Client Secret.

>Your Auth0 Authorization Server verifies the code, Client ID, and Client Secret.

>Your Auth0 Authorization Server responds with an ID Token and Access Token (and optionally, a Refresh Token).

>Your application can use the Access Token to call an API to access information about the user.

>The API responds with requested data.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
<br>
- Provides extra security via a code challenge.

4. What is Implicit Flow with Form Post?
<br>
- An access token is returned in a fragment.

5. What is Client Credentials Flow?
<br>
- Does not involve the user and access the token directly.

6. What is Device Authorization Flow?
<br>
- User gets a code to enter on another device.

7. What is Resource Owner Password Flow?
<br>
- User can request token by the owner's credentials like a username and password for an access token.

<details>
<summary>Things I want to know more about</summary>

Begin writing here...
  
</details>
