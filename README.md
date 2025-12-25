# convit
A fun Discord bot with games and money system.

## What is this?
Convit is a Discord bot where you can play games and earn coins. You can work, gamble, mine, craft items, and trade with friends. The bot has many features like leaderboards, shops, and daily quests.

### Main Features
- **Money and Stats**: Earn coins, manage energy and mood
- **Games**: Play slot machine, coinflip, scratchcard
- **Crafting**: Make items using recipes
- **Mining**: Dig for resources over time
- **Trading**: Buy and sell items with other players
- **Server Tools**: Guild funds and admin commands
- **Multi-language**: Works in different languages

## How to Setup

### What you need
- Python 3.10 or newer
- PostgreSQL database
- Discord bot token

### Step by step

1. **Get the code**
   ```bash
   git clone <your-repo-url>
   cd convit
   ```

2. **Install packages**
   ```bash
   pip install -r requirements.txt
   ```

3. **Setup database**
   - Get PostgreSQL connection URL from your database (or use websites)
   - Copy the queries in db.ddl file and execute them to setup the database.

4. **Setup .env file**
   - Copy `.env.example` to `.env`
   - Fill in the values:
   ```
   DISCORD_TOKEN=your_bot_token_here
   DB_URL=your_postgresql_connection_url_here
   GIPHY_API_KEY=your_giphy_api_key
   # ... and other keys you need
   ```

5. **Start the bot**
   ```bash
   python bot.py
   ```



### Database

The bot saves data in PostgreSQL. Run queries in `db.ddl` file first to create all tables.

### Bot permissions

Give your bot these permissions:
- Read messages
- Send messages
- Manage messages
- Embed links
- Use slash commands
- Add reactions

### Start playing

After setup, try these commands:
- `/help` - See all commands
- `/health` - Check your stats
- `/work` - Earn coins
- `/balance` - See your money
- `/leaderboard` - Top players



## License

GNU GPL v3
