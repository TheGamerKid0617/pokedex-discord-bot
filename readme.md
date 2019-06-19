# Botkit Discord Starter App
Starter Botkit Discord is a Discord bot with an interactive setup and coding guide. Click "show" to start following the guide.

The Install guide connects your Glitch app to a Discord app. It also teaches some important basic security guide. The Setup guide shows you how to add it to a Discord Server, keep it up and running, and add new functionality. 

It uses B
* Botkit: a handy bot building framework
* Discord.js: a node module for connecting to the Discord API
* Botkit Discord: A connector that allows you to use Bokit and Discord.js
* Uptime Robot: A monitoring service that helps keep your bot running 24/7


## The Code
This code is explained in the setup guide but here are some quick intros to each item you'll find on the sidebar

### assets
This is where you [can add images, sound files, and other media](https://glitch.com/help/how-do-i/).

### public/client.js
This is the interactive code for the setup guide.

### public/install.js
This is the interactive code for the install guide.

### skills/hears.js
This is an [Botkit](https://botkit.ai/) skill for your bot allowing it to respond to certain words it "hears" on the server

### views/index.html
This is the basic webpage for the setup guide

### views/install.html
This is the basic webpage for the install guide

### .env
This is a file for storing secure info like API keys

## bot.js
This is the base code initializing the bot by giving it to the Discord Api key and telling it where the skills files are

### package.json
This is a file that contains info about your project, like what [node modules it should install](https://glitch.com/help/how-do-i-add-an-npm-module-package-to-my-project/)

## readme.md
This is this file! It's full of helpful info.

## server.js
This contains the code that connects all the different pieces of the bot together so it can be started by package.json

## Get Started
Remix this app and click show! The install guide will walk you all the steps needed.