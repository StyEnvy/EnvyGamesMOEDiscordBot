Made by Styanatos of Envy Games
https://www.envy-games.com/

Made with Python 3.11.5 and the Discord.py library

This bot is designed to be a simple, easy to use discord bot for displaying the status and player count of your Myth of Empires Counties.

To setup the bot:

1. You need to create a discord token and invite the bot to your server. 
You can do this by going to the Discord Developer Portal and creating a new application. 
Then, create a bot and copy the token. You can then use that link to invite the bot to your server.

2.Open the .env and enter in your token

3. Open the config.json

  "EmbedChannelID": ""

  This is where your Discord Channel ID goes. This is the channel where the bot will send the embeds.

  "Name": "name-here",

  This is the user friendly name that will display in the embed for the county.

  "Description": "Envy Games",

  This is your -Description in your batch file to start your scene server. We recommend you put your server name here to make it easy to identify. 

  For example if mine is -Description="Envy Games US East Cluster. Envy-games.com"

  I can likely use "Envy Games" unless there is something similarily named. You can place the full description for optimal accuracy.

  "Port": 5004

  This is your -Port in the batch file to start your scene server. This is the port that the server is running on and shows in angela's systems.

  4. Keep debugging off unless I tell you to during troubleshooting. Keep logging off unless you have an issue.

4. Start the EnvyGames MOE Discord Bot.exe

Troubleshooting:

1. Delete the embed_data.json file and restart the bot. This will reset the embeds and should fix any issues with the bot not sending embeds. 
In the original version of this bot it was not supposed to be included and caused our test users to crash on startup. Simply deleting this file will resolve the issue.

2. If you do not see the embed appear in your server ensure:
  - The bot is online and you see it in your server
  - The bot has the correct permissions to send messages in the channel/server
  - The bot has the correct channel ID in the config.json

3. If your firewall or antivirus is flagging it... well I made this in visual studio code, and packaged it in powershell using Pyinstaller. 
It's a false positive and you can ignore it.
Upon request I can provide the source code for the bot to prove it's not malicious but prefer to protect my work from being forked.
