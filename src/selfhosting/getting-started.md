# Getting Started

We'll explain the process on how to setup your own server in this page.

To get started, you can start by installing the [server files](https://github.com/RimworldTogether/Rimworld-Together/releases/latest). Choose the appropriate version for your operation system, either Linux or Windows. We do not currently offer support for mac OS nor do we plan to in the future.

##Quick Start Guide
This guide will help you set up and run the server on a Windows installation.

1.	Create a Folder:
	Create a new folder on your desktop or preferred location.

2.	Extract the Server Files:
	Extract the server file/s into the newly created folder.

3.	Launch the Server:
	Run GameServer.exe (you can rename it if you prefer). A terminal window will appear and generate several folders and files. Once this process is complete, the server will be up and running.

4.	Connect to Your Server:
	You can join your server through the in-game menu, as described in the previous step. For more details, please refer to our client guide. (The Terminal window needs to be left open in the background)

5.	World Creation:
	The first client to join the server will be responsible for creating the world. We recommend using only the minimum enforced modlist during world creation to avoid potential issues.
	Essential mods for the server and client to run and connect properly include:
	Harmony, Core, Any DLC (if used, or you may disable the DLC), RimWorld Together

6.	Mod Recommendations for generation:
	Use Mods for world generation, use mods that add new world generation or tiles. After world generation, you can add any other mods that do not require a new save file to the server and apply as you would like Enforced/Optional/Forbidden.

##mods
If you encounter any mods that seem incompatible, please reach out to the mod's author and request a compatibility for the mod to be used with RimWorld Together. Alternatively, you may need to create the compatibility patch yourself.

## DLCs
You can find the DLC files on our [GitHub Page](https://github.com/RimworldTogether/Rimworld-Together) for server side use only.

DLCs are considered mods, so you can treat them as `mods`. 

## ActionValues file
You can change the cost in silver of actions in this file. Currently, you can use them on players.

## DifficultyValues file
You can set all the values for your enforced difficulty if are currently using that configuration. You can find all those stats under the custom storyteller option in RimWorld.

## EventValues file
You can change the cost in silver of events in this file. You can call those events on players.

## ServerConfig file
You can change various settings about the server, such as:
* The port being used by the server

* The IP being used by the server (when in doubt, leave it to `0.0.0.0`)

* The maximum amount of players connected at once.

* The maximum amount of time a client can go without responding the server in milliseconds. You can increase it if you have an unstable connection.

* Verboselogs gives you additional logging information on the server.

* DisplayChatInconsole does just that, the in game chat will be displayed on the console.

## ServerValues file
You can change if you want to allow custom scenarios for clients (ex :crashlanded, mechanitor, naked brutality).

## SiteValues file
You can change the various cost and production of sites in this file. You can find out more information about sites on out [Site Page](https://rimworldtogether.github.io/Guide/features/index.html#sites).

## Whitelist file
The file lets you configure if you want a whitelist or not. Simply put the in game usernames (the one used to log in) in between the brackets.

## WorldConfig file
This file stores all the world data. We do not recommend editing it mid run.

## TroubleShooting
For additional help with troubleshooting, please join our [Discord Server](https://discord.gg/NCsArSaqBW).

