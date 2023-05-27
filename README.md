# Boten Anna (README.MD in construction)

Boten Anna is a Discord Bot being developed using node.js in conjunction with discord.js and axios.

The first goal of this project is to study and gain hands-on experience in node.js development and web development in general.

The second goal is to present a user-friendly and customizable Discord Bot Blue-Print that includes fundamental moderation and utility commands. Additionally, it features a dynamic folder structure, which promotes better organization of commands and events for enhanced usability. Furthermore, this blueprint creates an environment that simplifies the implementation and maintenance of new commands, ensuring ease of adaptability.

## Table of Contents
- [Pre-Requisites](#Pre-Requisites)
- [config.json](#config.json)
- [Execution](#Execution)
- [Usage](#Commands)

## Pre-Requisites

### Node & Libs
This project uses Node.js in conjunction with discord.js and axios. It is possible to [Download Node.js from the official website](https://nodejs.org/en/download). Currently, boten anna is being developed using Node.js v18.16.0 and Discord.js v14

After downloading and installing node.js be sure to install Discord.js and axios using the following commands:

```bash
$ npm install discord.js
```
and

```bash
$ npm install axios
```

### Discord Application
The first step to set up the Bot is to create a Discord bot app. In case you are not sure about how to do this, I recommend reading this step of official Discord.js Guide: [Building your first Discord app](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot).

## config.json

Since the config.json contains sensitive information, it is listed on git.ignore. The first thing you need should do after the initial Node.js setup is to create a file named "config.json" in the root folder of the project and populate it with the following information.

**About guildID** - We currently use this parameter only to register the slashcommands on the target server. If by any chance you are deploying this application anywhere, you can use the exact same deploy-command script, changing the route to .applicationCommands(clientId).

If you dont know where to find your token, clientId or guildId, [check out the oficcial discord.js guide for more information](https://discordjs.guide/). 

```json
{
	"token": "Your bot Token goes here",
	"clientId": "Your application application ID goes here",
	"guildId": "This is your server ID "
}
```

## Execution

[Execution]

## Usage

[Usage]
