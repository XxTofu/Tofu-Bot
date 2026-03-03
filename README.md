# 🍽️ Rays Restaurant Discord Bot

A powerful moderation + economy Discord bot built using **discord.py** with Slash Commands (`app_commands`).

Designed for community servers, this bot combines secure moderation tools, automatic systems, fun interaction commands, and a full gambling-based economy — all using Discord’s built-in permission system.

---

## 🚀 Features

---

## 👋 Welcome System

Automatically welcomes new members when they join the server.

- Sends a welcome message in a specific channel
- Automatically assigns a predefined role

**Example:**
> Welcome @user to Rays's restaurant hope you enjoy!

---

## 🛡️ Moderation System (Permission-Based)

Uses Discord’s built-in permission checks instead of hardcoded roles.

### Commands

| Command | Description |
|----------|-------------|
| `/clear` | Deletes 1–100 messages |
| `/ban [reason]` | Bans a member |
| `/unban` | Unbans a member |
| `/kick [reason]` | Kicks a member |
| `/timeout [minutes]` | Timeouts a member |

### ✅ Safety Features

- Uses permission checks (`manage_messages`, `ban_members`, `kick_members`, `moderate_members`)
- Prevents kicking/banning higher or equal roles
- Prevents kicking yourself
- Checks bot permissions before executing
- Ephemeral moderation confirmations
- 100 message limit on `/clear`

---

## 💰 Economy System

Lightweight JSON-based economy system with passive income and gambling.

### 💵 Passive Income

Members automatically earn **$1–$5 every 10 seconds** when chatting.

- Cooldown prevents spam abuse
- Data stored in `balances.json`

---

## 🎲 Gambling System – `/roll`

Roll a 6, 8, or 20-sided dice and bet on the outcome.

### How It Works

1. Choose dice faces (6, 8, or 20)
2. Pick your number
3. Enter bet amount
4. Win with multiplier if correct

### Multipliers

| Dice | Multiplier |
|------|------------|
| 6 faces | 2x |
| 8 faces | 3x |
| 20 faces | 10x |

High risk, high reward system.

---

## 📊 Economy Commands

| Command | Description |
|----------|-------------|
| `/balance` | Check your balance |
| `/leaderboard` | Shows top 10 richest members |
| `/addmoney` | Admin-only add money command |

---

## 💕 Fun Commands

### `/ship`

- Generates custom ship name
- Random compatibility (1–100%)

**Example:**

Ship Name: Aleon

❤️ @Alex has a 87% compatibility with @Leon ❤️


---

### `/rob`

- Displays a user’s avatar
- Detects default Discord avatars
- Role-restricted access

---

## 📅 Utility Commands

| Command | Description |
|----------|-------------|
| `/joined` | Shows when a user joined |
| `/git` | Displays the bot owner's GitHub |

---

## ⚙️ Built With

- Python 3
- discord.py
- Slash Commands (`app_commands`)
- JSON data storage
- Role hierarchy protection logic
- Environment variable token management (`.env`)

---

## 🔐 Required Bot Permissions

- Manage Messages
- Kick Members
- Ban Members
- Moderate Members
- Manage Roles
- Read Messages
- Send Messages
