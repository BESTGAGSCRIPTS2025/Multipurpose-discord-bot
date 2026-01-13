# Multipurpose Discord Bot

## Overview
A feature-rich Discord bot built with Discord.js v13, offering moderation, music, games, social integrations, and many more features.

## Project Structure
- `index.js` - Main entry point
- `commands/` - Bot command files organized by category
- `slashCommands/` - Discord slash command implementations
- `handlers/` - Event handlers and utility functions
- `botconfig/` - Configuration files (JSON)
- `databases/` - Local database storage (enmap)
- `events/` - Discord event handlers
- `languages/` - Internationalization files
- `social_log/` - Social media integration handlers
- `assets/` - Static assets

## Configuration
The bot uses environment variables for sensitive data:
- `token` - Discord bot token (required)
- `memer_api` - Memer API key
- `clientSecret` / `clientID` - Spotify credentials
- `consumer_key` / `consumer_secret` / `access_token` / `access_token_secret` - Twitter credentials
- `fnbr` / `fortnitetracker` - Fortnite API keys
- `twitch_clientID` / `twitch_secret` - Twitch credentials

See `example.env` for all available environment variables.

## Running the Bot
```bash
node index.js
```

## Dependencies
- discord.js v13
- erela.js (music)
- enmap (database)
- Various APIs for social features

## Notes
- This is a Discord bot with no web frontend
- Requires a Discord bot token to function
- Music features require a Lavalink server
