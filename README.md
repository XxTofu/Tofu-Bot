#🍽️ Rays Restaurant Discord Bot

A powerful and fun moderation + utility Discord bot built using discord.py (app commands / slash commands).
Designed for community servers, this bot handles moderation, welcome messages, and even adds some fun interactive commands 💕

🚀 Features
👋 Welcome System

Automatically welcomes new members in a specific channel

Assigns a predefined role upon joining

Sends a friendly message:

"Welcome @user to Rays's restaurant hope you enjoy!"

🛡️ Moderation Commands

Role-based permission system for staff members.

Command	Description
/clear <amount>	Deletes a specified number of messages
/ban <member> [reason]	Bans a member
/unban <member>	Unbans a member
/kick <member> [reason]	Kicks a member (with role hierarchy checks)

✅ Staff role verification
✅ Prevents kicking yourself
✅ Prevents kicking members with equal or higher roles
✅ Ephemeral staff confirmations

📅 Utility Commands
Command	Description
/joined <member>	Shows when a user joined the server
/git	Displays the bot owner's GitHub profile
💕 Fun Commands
/ship <member1> <member2>

Generates:

A custom ship name

Random love compatibility percentage (1–100%)

Example:

Ship Name: Aleon
❤️ @Alex has a 87% compatibility with @Leon ❤️
/rob <member>

"Steals" and displays a user's avatar

Detects default Discord avatars

⚙️ Built With

discord.py

Slash Commands (app_commands)

Role-based moderation logic

Randomized fun features

🔧 Setup

Install requirements:

pip install discord.py

Run the bot:

python bot.py

Enter your bot token when prompted.

🔐 Permissions Required

Make sure your bot has:

Manage Messages

Kick Members

Ban Members

Manage Roles

Read & Send Messages
