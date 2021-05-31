## CRUD

+ In your own words, describe what each group of status code represents:

100’s = informational response – the request was received, continuing process.
200’s = successful – the request was successfully received, understood, and accepted.
300’s = redirection – further action needs to be taken in order to complete the request.
400’s = client error – the request contains bad syntax or cannot be fulfilled.
500’s = server error – the server failed to fulfil an apparently valid request.

+ What is a status code 202?

This doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.

+ What is a status code 308?
308 Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.

+ What code would you use if an update didn’t return data to a client?

204 No Content - A proper code for updates that don’t return data to the client.

+ What code would you use if a resource used to exist but no longer does?
410 code is an explicit indication that the requested resource used to exist, but it has since been permanently removed and will not be available in the future.

+ What is the ‘Forbidden’ status code?
403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.