# Build a Polymer App - From Authentication to Calling an API

Build your first Polymer web app. Call an API and authenticate with [JSON Web Tokens](http://jwt.io) and local storage.

## Dependencies

* [Node.js](http://nodejs.org)
* [Bower](http://bower.io) `npm install bower -g` (if adding additional packages)
* [nodejs-jwt-authentication-sample](https://github.com/auth0-blog/nodejs-jwt-authentication-sample)

## Setup

1. Install the Polymer CLI: `npm install -g polymer-CLI`
2. Clone this repo into the folder of your choice
3. Clone [nodejs-jwt-authentication-sample](https://github.com/auth0-blog/nodejs-jwt-authentication-sample) into a different directory
4. Serve the API via `node server.js`; runs on [http://localhost:3001](http://localhost:3001)
5. Serve the Polymer project from the project folder: `polymer serve` (can be accessed in browser at [http://localhost:8080](http://localhost:8080), or add the `--open` flag to auto-launch in your default browser)
