# Build a Polymer App - From Authentication to Calling an API

Build your first Polymer web app. Call an API and authenticate with [JSON Web Tokens](http://jwt.io) and local storage. Read the full tutorial here: [Build Your First App with Polymer and Web Components](https://auth0.com/blog/build-your-first-app-with-polymer-and-web-components/).

## Dependencies

* [Node.js](http://nodejs.org)
* [Bower](http://bower.io) `npm install bower -g`
* [nodejs-jwt-authentication-sample](https://github.com/auth0-blog/nodejs-jwt-authentication-sample)

## Setup

1. Install the Polymer CLI: `npm install -g polymer-CLI`
2. Clone this repo into the folder of your choice
3. Run `bower install` to install Bower components
4. Clone [nodejs-jwt-authentication-sample](https://github.com/auth0-blog/nodejs-jwt-authentication-sample) into a different directory
5. Serve the API via `node server.js`; runs on [http://localhost:3001](http://localhost:3001)
6. Serve the Polymer project from the project folder: `polymer serve` (can be accessed in browser at [http://localhost:8080](http://localhost:8080), or add the `--open` flag to auto-launch in your default browser)

## What is Auth0?

Auth0 helps you to:

* Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, amont others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
* Add authentication through more traditional **[username/password databases](https://docs.auth0.com/mysql-connection-tutorial)**.
* Add support for **[linking different user accounts](https://docs.auth0.com/link-accounts)** with the same user.
* Support for generating signed [Json Web Tokens](https://docs.auth0.com/jwt) to call your APIs and **flow the user identity** securely.
* Analytics of how, when and where users are logging in.
* Pull data from other sources and add it to the user profile, through [JavaScript rules](https://docs.auth0.com/rules).

## Create a free Auth0 account

1. Go to [Auth0](https://auth0.com/signup).
2. Use Google, GitHub or Microsoft Account to log in.

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
