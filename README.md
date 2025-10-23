# papa-cheems-bot
This is a simple Discord bot created by following the Discord Developer Portal "Getting Started" guide. It's a simple webhook bot that plays Rock-Paper-Scissors and rolls dice.

## Features

* Responds to the `/challenge` command (Rock, Paper, Scissors).
* Includes a custom `/dice` command that rolls a 6-sided die.

## What I Learned

* How to set up a Node.js server with Express.
* How to register and handle Discord slash commands.
* How to use `ngrok` to tunnel webhooks to a local server.
* How to manage environment variables (`.env`) for secure tokens.

## How to Run This Project

1.  Clone this repository: `git clone ...`
2.  Install dependencies: `npm install`
3.  Create a `.env` file and add your `DISCORD_TOKEN`, `CLIENT_ID`, and `PUBLIC_KEY`.
4.  Run the command registration: `npm run register`
5.  Run the bot: `npm run start`
