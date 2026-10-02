
# Voidex Store Official — Setup Guide

## 1. Requirements

Install the following:

- Node.js 18 or newer
- npm
- Discord Application
- Discord Bot Token

## 2. Install Dependencies

Open a terminal in the project directory:

```bash
npm install
```

## 3. Create Your Discord Bot

1. Open the Discord Developer Portal.
2. Create or select an application.
3. Open the Bot section.
4. Create a bot user.
5. Copy the bot token securely.
6. Enable the required intents.
7. Invite the Bot to your server with the necessary permissions.

**Never share your bot token publicly.**

## 4. Configuration

Open `config.json` if your project includes it.

Update the required settings, such as:

- Bot Prefix
- Developer IDs
- Embed Color
- Footer Text
- Support Server

Use the configuration format expected by your project.

## 5. Environment Variables

If your project uses environment variables, create a
private `.env` file.

Example:

```env
TOKEN=your_discord_bot_token
```

Use the exact variable names expected by the source code.

Do not upload secrets to public repositories.

## 6. Start the Bot

Run:

```bash
npm start
```

If the project has a setup script, you can run:

```bash
npm run setup
```

## 7. Troubleshooting

### Bot Does Not Start

- Check your Node.js version.
- Run `npm install`.
- Verify configuration values.
- Review the terminal error.

### Bot Is Offline

- Verify the bot token.
- Check that the hosting process is running.
- Review Discord intents.

### Commands Do Not Work

- Check Bot permissions.
- Verify the command prefix.
- Review the console logs.

## 8. Security

- Keep your token private.
- Use minimum required permissions.
- Do not commit secrets.
- Review third-party dependencies.

## 9. Support

Contact MARUF through the official support server.

---

Copyright © 2026 MARUF.
All rights reserved.
