Implement a filter using ApiFilter. The application should allow users to securely generate an API key, expose a controller endpoint for generating that key, and store the key.

Inside the filter, validate every incoming request by checking whether it contains a valid (and non-expired) API key.

If the key is valid, allow the request to proceed to the controller.

If the key is missing, invalid, or expired, return an appropriate response with the correct HTTP status code.
