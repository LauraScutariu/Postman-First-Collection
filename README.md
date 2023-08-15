# Postman-Project

What is Postman?

Postman is a tool that allows us to easily work with APIs.
Postman is used to build HTTP requests that we send to the server running the API.

To use an API you need to read the API documentation. We're using Spotify API whose documentation can be found in the resources section of this lesson below.
Work in Postman is organized in Workspaces.
A status code 200 (or any status like 2XX) indicates that the request was successful.

📚 - Resources

[Spotify API documentation](https://developer.spotify.com/documentation/web-api/concepts/scopes#user-follow-read)

### HTTPS

The API we are using uses the HTTPS protocol.

HTTPS stands for Secure Hypertext Transfer Protocol.

HTTPS ensures that the connection is encrypted.

All APIs should use HTTPS.

From our point of view HTTP and HTTPS are the same.

The HTTP request message will contain:
- URL (address)
- Request method (GET, POST, PUT, ...)
- Headers (User-Agent: Postman)
- Body
  
The HTTP response message will contain:
- Status code (200, 404, 500, ...)
- Headers
- Body

[Here]() you will find tests run in Postman in the API documentation presented previously. Enjoy !
