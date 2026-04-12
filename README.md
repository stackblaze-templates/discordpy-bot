# Discord.py Bot
Discord bot built with discord.py (Python).
## Local Development

    cp .env.example .env
    # Add your bot token
    pip install -r requirements.txt
    python bot.py

## Adding Commands
Add cogs in the cogs/ directory. See cogs/sample.py for an example.
## Deploy on StackBlaze
This template includes a stackblaze.yaml. Set DISCORD_TOKEN in env vars.
