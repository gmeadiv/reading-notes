# CRUD

## Status codes based on REST methods
- In your own words, describe what each group of status code represents:
  - 100’s = informational status codes: request received and server will try to comply with request
  - 200’s = success code: request accepted
  - 300’s = redirection codes tell client that the resource they're requesting isn't at this location anymore
  - 400’s = client error codes tell client they sent an invalid request
  - 500’s = server error codes indicate problem with the server, try again
- What is a status code 202? Tells client the request was valid but the response is still processing
- What is a status code 308? Permanent redirect gives client a new URL and instructs them not to use the current one again
- What code would you use if an update didn’t return data to a client? 500's
- What code would you use if a resource used to exist but no longer does? 300's
- What is the ‘Forbidden’ status code? Client doesn't have permission to access the resource