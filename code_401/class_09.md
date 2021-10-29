# Authorization / Authentication

## What header(s) are used in authentication and authorization

- authentication: Basic [ encoded password ]

- authorization: Bearer [ encrypted token ]

## What is safe to put into a JWT

- letters and numbers, special characters screw up the decryption

## How are JWTs validated

- the token contains a secret which is compared to one stored securely by the server

## Document the following Vocabulary Terms

- RBAC: Role Based Access Control

- User Roles: by assigning certain capabilities to specific roles, and those roles to users, you can control the things users are allowed to do

- JWT Token: An encrypted token kept by the user to verify their identity
