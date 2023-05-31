# Auth0 Reading

## What is OAuth?
OAuth, or Open Authorization, is a protocol that allows an application to authenticate against a server as a user, without requiring passwords or other sensitive information.

## Give an example of what using OAuth would look like.
For example, when you use an app and it offers the option to "Log in with Google" or "Log in with Facebook," that's OAuth in action. You're authorizing the app to access some information from your Google or Facebook account.

## How does OAuth work? What are the steps that it takes to authenticate the user?
OAuth works by following these steps:
1. The user initiates the process by attempting to log in to a service using their credentials from a different service.
2. The service then requests authorization from the user's account on the other service.
3. If the user approves the authorization request, the original service receives an access token it can use to authenticate the user.

## What is OpenID?
OpenID is an open standard and decentralized authentication protocol that allows users to be authenticated by cooperating services, known as Relying Parties, using a third-party service.

## What is the difference between authorization and authentication?
Authentication verifies who a user is, while authorization determines what that user can access or do. Authentication precedes authorization.

## What is Authorization Code Flow?
Authorization Code Flow is an OAuth 2.0 flow that involves the application directing the user to an authorization server, the user authenticating, and then the server returning an authorization code to the application, which it can exchange for an access token.

## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
This is an extension of the Authorization Code Flow, designed for public clients. It mitigates the risk of interception of the authorization code by generating a unique code verifier for each authorization request.

## What is Implicit Flow with Form Post?
This is a simplified OAuth 2.0 flow where access tokens are returned immediately without an extra authorization code exchange step. It was designed for applications that can't maintain the confidentiality of their client secret.

## What is Client Credentials Flow?
Client Credentials Flow is an OAuth 2.0 protocol flow where the application authenticates itself to an authorization server with its client ID and client secret, and gets an access token in return.

## What is Device Authorization Flow?
Device Authorization Flow is an OAuth 2.0 flow designed for devices that either don’t have access to a browser or have limited input capabilities. The device gives the user a URL and a code, the user visits the URL and enters the code, authorizing the device.

## What is Resource Owner Password Flow?
This is an OAuth 2.0 flow where users provide their username and password directly to the application, which uses them to request an access token from the authorization server.
