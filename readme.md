# Virtual

A legacy JavaScript Discord bot project with a modular command and event structure.

> **Status:** Legacy / experimental codebase. Not recommended for production deployment without modernization and security review.

## Overview

Virtual uses Node.js and discord.js v12. Its dependencies cover community bot features such as music, moderation utilities, giveaways and image processing; individual capabilities may require additional configuration.

## Project structure

| Path | Purpose |
| --- | --- |
| `bot.js` | Bot entry point |
| `komutlar/` | Command modules |
| `events/` | Event handlers |
| `util/` | Supporting utilities |
| `ayarlar.json` | Local configuration |

## Development

The original manifest targets Node.js 12, which is end-of-life. Review the code, upgrade to a supported Node.js release and update dependencies before running the bot.

The existing start script is `npm start`. Configure credentials locally and never commit Discord tokens or other secrets.

## License

The original package manifest declares MIT. Review any upstream notices and applicable third-party licenses before reuse.
