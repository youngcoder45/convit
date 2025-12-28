# convit
A helpful Discord bot with features of added games,and economy.

# What is this?

Convit is a very entertaining Discord bot that offers a variety of activities such as coin collecting and playing games. Some things that can be done in Convit include working, placing a bet, mining, crafting objects, and trading.

### MAIN FEATURES
- Money & Stats: Collect coins, monitor energy and mood levels
- Games: Slot Machine, Coin Flip, Scratchcard
- Crafting: Create items using recipes
- Mining, Mining: Dig for resources over time
- Trading: Buy and sell with other players

- Server Tools: Guild funds and admin commands

- Multi-language support: Supports multiple languages

# How to Setup

### Things You’ll Need
- Python 3.10+
- PostgreSQL database
- discord bot token

### Step by Step

1. Get the code
- git clone
- cd convit

2. Install Packages
- pip install -r requirements.txt

3. Database setup
- Find your connection URL for PostgreSQL (from your database or a hosting website)
- Copy the queries from the file db.ddl and execute them to create the database

4. Setup .env file
- Copy .env.example to .env
- Add values to those key
- .and any other keys you may need

5. Start the bot
- python bot.py

### Database
The bot utilizes PostgreSQL for storage.
Run all the queries in db.ddl for table creation.

### Bot permissions
The bot needs the following permissions:
- View Channels
- Send Messages
- Manage Messages
- Embed Links
