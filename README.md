# netflix-receive-pin-discord-bot
<br />
<div align="center">
  <img src="./assets/netflix.svg" alt="Logo" width="75" height="75">
  <img src="./assets/discord.png" alt="Logo" width="80" height="80">
  <h1 align="center">Netflix Receive Pin Discord Bot</h1>
</div>

## Description

This GitHub repository hosts a Discord bot designed to receive Netflix PIN code via Discord channels.

## Usage

First, you need to create an email app password and a discord bot. If you don't know how to, just search it.

Then, fork this repository and add secret keys:
- `EMAIL`: email address which receive netflix pin when requested.
- `PASSWORD`: email app password.
- `TOKEN`: discord bot token.

Finally, use it in your discord server. The prefix is **!**, there are 2 commands (you can add more for your needs):
- **!hello**: just make sure the bot is active.
- **!verify**: get the pin code, make sure you request the pin code before use this command.

