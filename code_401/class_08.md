# Access Control

1. When is Basic Authorization used vs. Bearer Authorization?

- basic auth is used for HTTP request

- bearer auth creates access tokens which are used for API requests

2. What does the JSON Web Token package do?

- it securely transmits information as a JSON object

3. What considerations should we make when creating and storing a SECRET?

- don't store unencrypted secrets in git repos

- use .gitignore

## Document the following Vocabulary Terms

- encryption: scrambles data so only users with the correct key can unscramble it

- token: used by bearer auth to authenticate API requests

- bearer: whoever possesses the token

- secret: authentication credentials which grant access to systems and data

- JSON Web Token: it securely transmits information as a JSON object
