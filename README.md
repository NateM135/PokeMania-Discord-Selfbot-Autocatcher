# PokeMania-Discord-Bot-Autocatcher

Autocatcher Developer: NateM135

PokéMania Developer: Triickstr#0420

[Click Here to Join The Official Server for PokéMania](https://discordapp.com/invite/hwMG5J9)

[Click Here to Invite PokéMania to Your Server](https://discordapp.com/oauth2/authorize?client_id=627952266455941121&scope=bot&permissions=388160)

This is a simple autocatcher for the Pokecord clone PokéMania. Just like Pokecord, PokéMania spawns pokemon based off normal activity. Thus, autocatching is possible.

# Features

- Autocatching
- Webpage (html file) to show the pokemon you have caught
- Random dialogue to make it seem as if you are not botting
- Minor anti bot-detection settings and configurations
- Tracking for Pokemon captured/escaped/money earned

See Changelog.md to get more information about updates/bugs/features.

In the future, the following features are planned:
- Legendaries support/special circumstances/recognition
- Commands to show pokemon during the current session
- JS to automatically update webpage/status.html
- Optional DM Reports to the owner account about Pokemon captured
- Automatic Money Command Scheduling/Out of Money Detection
- Better report page formatting

To suggest features, open an issue or DM me on reddit (NateM135)

## Images

Here is a gif of the bot in action.

 ![autocatcher_example](https://i.imgur.com/Bpw6CqS.gif)


Here is a picture of the webpage (status.html) after running the bot in a popular server for a few minutes. 

 ![autocatcher_summary](https://i.imgur.com/cri2QYc.png)

# WARNING

**SELF BOTS ARE AGAINST DISCORD TOS. I AM NOT RESPONSIBLE FOR YOUR ACCOUNT/YOUR ACTIONS**


# Setup

There are several things you would need to setup. Download the files and open the file ``setup.py``. 

The autocatcher supports multiple servers, and thus you need to configure both the server/prefix for the bot on that server. 

The file you will do this in is ``guilds.py``. In order for the bot to work in a server, the server id along with the bot's prefix in that server MUST, i repeat MUST be in guilds.py. If not, the messages are ignored. Simply make an entry like the ones that are already there as examples. 

``TOK`` is your account/selfbot token. If you need help getting your user account token, see [this guide here](https://github.com/Tyrrrz/DiscordChatExporter/wiki/Obtaining-Token-and-Channel-IDs).

``DELAY`` is how long the bot should wait before catching a pokemon after it spawns. It has to be an integer. The default value is 2 seconds. 

``OWNER ID`` is your main account's user ID. This will be used to control the bot account in future updates. For now, the value is unused in the actual bot.

``SELFBOT UID`` is the selfbot account's ID.

``CAPTURE CHANCE`` is the chance that you capture a pokemon that spawns. 100 = 100%, 90 = 90%, etc.

``BALL_TYPE`` is the type of pokeball you use. There are three choices: ``POKEBALL``, ``GREATBALL``, ``ULTRABALL``. Ultraballs are sustainable/you won't have any issues using only Ultra Balls. Ultra Balls have the highest capture rate (80%) but are the most expensive.

``BUY_BALL_AMOUNT`` is the amount of balls the bot will buy when you run out. The bot will buy this amount of the chosen Pokeball.

Now, open up ``status.html`` in your web browser. You will have to refresh the page to see new updates such as money, pokemon captured, pokemon escaped, etc.

You will need Python3 as well as a modules installed.

Assuming you have Python installed, type ``python --version``. If it shows anything in the ``2.x`` range, this will not work and you need Python3. Try typing ``python3 --version`` to see if you have Python3 installed on your machine. Whichever command's version is ``3.x`` is the one you will use for the rest of the guide.

I will finish this guide in a future update. 

## Support

Open an issue on github or send a pm on reddit if you need help setting it up.




