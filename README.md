# Twilio Node.js app for generating an access token
This will guide you through generating an access token for Twilio using Node.js.
## Prerequisite

- This project requires that you have Node.js installed on your system. You can install [Node.js](https://nodejs.org/) here if you don't have it installed.
- You need a Twilio API KEY. Get it [here](https://twilio.com/)

## Setup

- Clone the repository to your system by running the command:

```sh
git clone https://github.com/dongido001/TwilioNodeServer.git
```

- cd into the project folder and install all packages:

```sh
  cd TwilioNodeServer && npm install
```

- Create your configuration file:

```sh
   cp .env.example .env
```

- Next, open up `.env` file in your editor and update your Twilio API KEYs.

```
TWILIO_ACCOUNT_SID=TWILIO_ACCOUNT_SID  # Your Account SID
TWILIO_API_SID=TWILIO_API_SID # Your API Key SID
TWILIO_API_SECRET=TWILIO_API_SECRET # Your API Key SECRET
```

Run the app

```sh
  node app.js
```

- If everything goes fine, Node.js server will be running on: `http://localhost:3000/`

## Example use case

To generate an access token, visit http://localhost:3000/token?identity=dongido

In the case, `dongido` is the identity of the user we want to generate an access token for.
