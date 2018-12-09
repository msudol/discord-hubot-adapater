# hubot-discord-adapater
A hubot adapter for the Discord.js API

## Information

More coming soon.

## Setup

Setup is quite easy just use NPM to install this adapter from github:

    npm install https://github.com/msudol/hubot-discord-adapter.git
    
Then run hubot with the adapter flag 

    ./bin/hubot -a discord-adapter
    
You may also use a .json file with the env object set.

    "env": {
        "HUBOT_DISCORD_TOKEN": "your token here",
        "HUBOT_DISCORD_AUTOCONNECT": false
    }
 

Remember you need to have an environment variable called ``HUBOT_DISCORD_TOKEN`` with your Bot token which you can get here: https://discordapp.com/developers/applications/me