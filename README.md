# Node.js app for generating Twilio access token.

## How to run

- Install all packages:
```
     npm install
```
- Create your configuration file and update .env file with your Twilio: Token
```
   cp .env.example .env
```
- Run the app
```
  npm start
```

## Example:

 - http://localhost:3002/token?identity=dongido

## Note:

This app is not secured! This means any user can use it to generate token. If you intend to use this in real world, make sure to add authentication.
