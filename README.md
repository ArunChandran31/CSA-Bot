# CSA Bot – Discord User Management Bot

CSA Bot is a Discord bot built with Python and `discord.py`, designed to help manage users in a Discord server with features like role management, content moderation, direct messaging, polls, and more. It’s lightweight, beginner-friendly, and useful for communities looking to automate basic moderation and interaction tasks.

---

## Features

- Welcome new members with a DM.
- Basic content moderation (auto-delete offensive messages).
- Assign or remove roles (e.g., `"Clan Chief"`).
- Respond to user messages (`!hello`, `!reply`).
- DM users from the server.
- Create simple polls with reactions.
- Permission-based secret command using role check.
- Logs bot events to `discord.log`.

---

## Getting Started

### Prerequisites

- Python 3.8+
- Discord bot token
- `discord.py` library
- `.env` file for token management

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/csa-bot.git
   cd csa-bot
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variable:**

   Create a `.env` file in the root directory:

   ```env
   DISCORD_TOKEN=your_discord_bot_token_here
   ```

4. **Run the bot:**

   ```bash
   python bot.py
   ```

---

## Commands

| Command     | Description                                     |
| ----------- | ----------------------------------------------- |
| `!hello`    | Bot greets the user.                            |
| `!assign`   | Assigns the "Clan Chief" role to the user.           |
| `!remove`   | Removes the "Clan Chief" role from the user.         |
| `!dm <msg>` | Sends a private DM to the user.                 |
| `!reply`    | Bot replies to the user's message.              |
| `!poll <q>` | Creates a poll with 👍 and 👎 reactions.        |
| `!secret`   | Accessible only to users with the "Clan Chief" role. |

---

## Log File

Bot logs are written to `discord.log` for debugging and monitoring.

---

## Tech Stack

* **Language:** Python
* **Library:** discord.py
* **Logging:** Python’s built-in logging module
* **Environment Handling:** python-dotenv

---

## Permissions Required

Make sure your bot has the following permissions in your Discord server:

* Read Messages
* Send Messages
* Manage Roles
* Add Reactions
* View Channels

---

## Author

**Arun Kumar C**
Project: CSA Bot – Discord Bot

---
