**DISCLAIMER**: FlappyGrant Auth ***DOES NOT*** use the current system [FlappyGrant's Website](https://www.flappygrant.com/?from=github) uses. It uses a system more like Google sign-in's.

# FlappyGrant Auth
Use a customized FlappyGrant sign-in system in replace of Google's nonsense.
Have you ever needed google sign-in but you don't want to deal with nonsense such as verification and limiting? FlappyGrant Auth is here in a clutch!

## Features
- **Account information** is saved in the user's localStorage (Browser storage) for easy one-click access.
- **No project setup required**, just redirect the user to a login link specifying your project details and a post-sign-in link (most of the time, a dashboard).
- **An API** for your website's dashboard to get the user's information. The API handles redirecting to our login page if your code supplies your website information.
- **No backend required**, our API handles sending user information to your dashboard/frontend. However, it is recommended to save user data on your own backend to prevent constant re-sign-in.

## Drawbacks
- **Not as popular**, so users might need extra help. However, our login page does supply a tutorial in case they're new.
- **Bugs might make user experience lower**, so we provided a bug report email.

This repository holds the backend and frontend code for FlappyGrant Auth, and you may run it yourself or modify it for your own auth system.
