# Twilio Node.js app for generating an access token
This will guide you through generating an access token for Twilio using Node.js.
## Prerequisite

- This project requires that you have Node.js installed on your system. You can install [Node.js](https://nodejs.org/) here if you don't have it installed.
- You need a Twilio API KEY. Get it [here](https://twilio.com/)

## Setup

Clone the repository to your system by running the command:

```sh
get clone https://github.com/dongido001/TwilioNodeServer.git
```

cd into the project folder and install all packages:

```sh
  cd TwilioNodeServer && npm install
```

Create your configuration file:

```
   cp .env.example .env
```

Next, open up `.env` file in your editor and update your Twilio API KEYs.

Run the app
```
  npm start
```

If everything goes fine, NodeJs server will be running on: `http://localhost:3000/`

## Use case

To generate an access token, visit http://localhost:3000/token?identity=dongido

In the case, `dongido` is the identity of the user we want to generate an access token for.
