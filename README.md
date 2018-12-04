# spotify-get-token
Server proxy to get the JWT token from Spotify

## Install

1. Fetch dependencies: ```npm install```
2. Run server: ```npm start```
3. Test server is running opening url ```http://localhost:3000``` in your browser.

## Usage

>In order to get a JWT token you need first to register you app in [Spotify Developers API website](https://developer.spotify.com/dashboard)

When you have registered your app you will get the 'Client ID' and a 'Client Secret', this app relays on them to get or renew the JWT token.

The url is ```http://localhost:3000/spotify/:client_id/:client_secret``` where you have to replace *:client_id* and *:client_secret* by the corresponding values.

> It can be used using a browser as well as using Ajax to reach the server.
