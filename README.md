# Discord Bot Reptile 

An AI Discord bot built with Python and Discord.py featuring moderation, role management, polls, and AI chatbot integration.

## Features

- Welcome new members
- AI chatbot support
- Auto-delete banned words
- Assign and remove Gamer role
- Role-protected secret commands
- Direct messaging
- Poll creation


## Commands

| Command | Description |
|----------|-------------|
| !hello | Greets the user |
| !assign | Assign Gamer role |
| !remove | Remove Gamer role |
| !secret | Access secret command |
| !dm <message> | Send yourself a DM |
| !reply | Bot replies to your message |
| !poll <question> | Create a poll |
| !gpt <prompt> | Ask the AI assistant |

## Installation

```bash
git clone https://github.com/Sceptile36/Discord-Bot-Reptile.git
cd Discord-Bot-Reptile
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file:

```env
DISCORD_TOKEN=your_discord_token
GROQ_API_KEY=your_api_key
```

## Technologies Used

- Python
- Discord.py
- Python-dotenv
- Gemini API

## Future Plans

- AI image generation
- Conversation memory
- Music commands
- Moderation dashboard

## Author

Created by Sceptile36
