# API tetsing on Spotify APP Project

Spotify Web API enables the creation of applications that can interact with Spotify's streaming service, such as retrieving content metadata, getting recommendations, creating and managing playlists, or controlling playback.

The Spotify Web API provides a wide range of functionality for developers, including:

- Retrieve data from your favourite artist,album or show ;
- Search for Spotify content ;
- Control and interact with the playback,play & resume ,Seek to a position or retrieve your queue ;
- Manage your personal library,by creating a new playlist and adding your favourite tracks to it ;
- Get recomandation based on the music you listen the most.
  And much more! You can find a complete list of available endpoints in the API Reference. 

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

The HTTP request message will contain:
- URL (address)
- Request method (GET, POST, PUT, ...)
- Headers (User-Agent: Postman)
- Body
  
The HTTP response message will contain:
- Status code (200, 404, 500, ...)
- Headers
- Body

[Here](https://github.com/LauraScutariu/Postman-Project/blob/c6b7fbd8c9aa006815edb81945279405397d3a41/Spotify-postman_collection.json) you will find one collection which run in Postman in the API documentation presented previously. Enjoy !
