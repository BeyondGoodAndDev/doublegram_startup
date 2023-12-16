#Doublegram Startup Edition - Definitive Telegram scraping & adding tool

![Logo](https://iili.io/JIb3rp2.gif)




Add thousands of users to your groups and channels using your Telegram accounts. Doublegram let you do that easily and in an automatic and personalized way. 

**OFFICIAL TELEGRAM GROUP (English - Italiano): www.t.me/doublegram_official**

**OFFICIAL TELEGRAM SUPPORT (English - Italiano): www.t.me/doublegram_owner**

Doublegram is available in three editions, the Startup Edition is now free and open source. And this is the first public stable release of Doublegram!

You can learn more about the other editions on www.doublegram.com 


**A Documentation will be added soon, for now remember to add an account to Doublegram first (disable your 2fa before, you can enable it again after your account is connected to Doublegram), then scrape some members and then add them somewhere**

## Update instructions:
Just copy and replace all the folders from your current version of Doublegram into the folder of the new version

## Compatibility:
Windows, MacOS, Linux.
Not officially yet but it seems to work on Android! (You'll need a Python IDE).

## What you need:
- Python >= 3.8
- pip installed
- run "**pip install telethon==1.26**"
- To start Doublegram run this in the same folder of start.py file: "**python3 start.py**" (or "py start.py" or "python start.py" for windows users)

## How it works
- Use your Telegram accounts to scrape the list of the members of a group where members are visible or in all of your groups and channels and put them in a list with Doublegram. You can scrape from multiple places and create a unique list of members
- Invite all the account you want to use for automatized invitation in the group or channel where you want to add the users that are in the list you made.
- Now select the filter and the regulation of the adding as your needs
- Run an adding task to add the users from the list to one of your group or channel

## What you get
A regularly updated software (it even tell you when there is an update if you don't mess with start.py and banner.py files), the definitive adding & scraping tool with tons of new features that elevate the standards of those software. Stop spending money on fake users, fake bots, or spend money in general when you can have it for free. Doublegram Startup respond to all the common needs when talking of scraping and adding users. 

## Preview

https://www.dblgrm.me/img/adding.webm 
https://www.dblgrm.me/img/scraping.gif 
https://www.dblgrm.me/img/enabledisable.gif 
https://www.dblgrm.me/img/options.gif 


## Features
 - 3 differents scraping methods (Standard, Recents users and by first letter method)
 - Scrape members from multiple groups and channels* and create a unique list of users ready to be added in the group or channel you need
 - View stats of scraped members like nums of bot, number of users without picture, number of users with visible phone number, so you can edit the list if you need to (it will be a CSV file)
 - 2 Methods of scraping in one, if the members of the target are visible you can scrape it for sure.
 - Duplicated users (for example users that were in 2 groups you took members from) will be removed automatically from the list
 - Create a new list or add users to the current one when you scrape members
 - Add only members with a username when you run an adding task (adding task = adding members from the list in your group or channel)
 - Set pause between using an account and another
 - Set max number of requests per account before changing account during adding task
- Set members list start point when run an adding task (you can start where you left the last time)
- Set pause between one adding request and another
- Set almost any pause with a random value between a range, to not look like a bot
- Connect unlimited Telegram accounts
- Easily choose targets groups and channels through the groups or channels your account are in
- Autobackup of your accounts everytime you add or delete an account and when overwrite your accounts list
- Account analysis to check flood and limitation on your accounts and also datas of your accounts
- Set user for testing flood and limitation*
- Run on a VPS and in background*
- To save requests that may fail, when you add users in a group or channel Doublegram will automatically remove from the requests the users that are banned or kicked in the destination group or channel
- To minimize the unsuccessfull requests, before you add users in a group or channel Doublegram will automatically remove the users that are already in the destination group or channel
- Run multiple sessions of Doublegram without limit on the same device and run multiple tasks at the same time!

## How to run in background
You can use screen: $ **screen -s Session_Doublegram**
then start as said above. After that you can close the terminal when you want and it will continue running. To reopen: $ **screen -ls** to list the active sessions, then $ **screen -r 12345** (change "12345" with the number of your session)

## Installation video
[![Doublegram Installation](https://img.youtube.com/vi/IyE0le_DJTg/0.jpg)](https://www.youtube.com/watch?v=IyE0le_DJTg)

