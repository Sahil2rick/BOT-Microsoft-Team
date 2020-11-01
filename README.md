# Microsoft Teams BOT

This bot will attend the online classes (or meetings) held on Microsoft teams, according to the given timetable by you and you will get the nortification for all the classes on Discord Have fun and Never miss your class.
## Notifications on Discord 

- ![This is how list view looks like](https://i.imgur.com/icG7NzB.png)
- ![This is how list view looks like](https://i.imgur.com/aeygXS4.png)
## Configure

There are few things you need to configure before running this bot.

 - Open Microsoft teams on your browser, login to your account, change the dashboard view to list view (from grid view), so that your classes are displayed in a list view. 
 - ![This is how list view looks like](https://i.imgur.com/SSDo8c6.png)
 - Open *bot.py*, and put your microsoft teams credentials in the **CREDS** dictionary. 
 - Example - `CREDS  = {'email' : 'myemail@email.com', 'passwd':'''mypassword'''}`
 - Open *discord_webhook.py* and put your discord webhook URL in the **webhook_url** variable. 
 - Example - `webhook_url = "https://discordapp.com/...."`
 - Make sure that the timezone of the PC is correct. If you're running the bot on cloud, you may want to manually change the timezone of the virtual machine to an appropriate time zone (i.e., the timezone that your online classes follow)

## Install

 - Clone the repository `git clone https://github.com/Sahil2rick/BOT-Microsoft-Team`
 - Install requirements.txt `pip install -r requirements.txt`
 

## Run the bot

 - Run the bot `python bot.py`

Written on Python3.
With Love Sahil Saini
## Want Help In Installing?

Go to https://sahilsaini.co
or Send me E-mail - sahil@sahilsaini.co
or you know where I will be (10 magical numbers)
