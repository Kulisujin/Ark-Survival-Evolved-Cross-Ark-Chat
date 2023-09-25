# Ark-Survival-Evolved-Cross-Ark-Chat

Introduction
The ARK: Survival Evolved Cross-Ark Chat Logger is a tool for server administrators to monitor and log activities in multiple ARK: Survival Evolved game servers. It allows you to categorize and relay server activities, such as player messages, admin commands, and tribe events, to a Discord server for further management and notifications.


Features
Discord Integration: The tool is integrated with Discord, allowing you to relay server activities to your Discord server.

Log Parsing: Monitor ARK game servers and parse log messages into different types, such as server, admin, tribe, and player. Take actions based on message types, including logging, and sending messages to Discord webhooks if enabled.

Server Configuration: Configure multiple ARK game servers to monitor.

Settings: Configure various settings related to Discord integration, including Discord webhook URLs and logging settings.

Import and Export Settings: Easily import and export program settings to and from a .cfg file.


Getting Started
Prerequisites
Before you start, ensure you have the following prerequisites:

A system running Windows (the program is written in C# and intended for Windows use).
The ARK server must have been ran at least twice for the files to be created.
Server Admin Logs must be enabled.
  In ASM, this option is "Enable Server Admin Logs" under Administration
The network Local IP must be manually entered.
  In ASM, this option is "Local IP" under Administration
RCOM must be enabled.
  In ASM, this option is "Enable RCON" under Administration

Installation
Download the program.

Extract the downloaded archive to your preferred location.

Configuration
Start the ARK: Cross-Ark Chat program.

Configure your settings, including Discord integration and server settings.

Settings
The settings include various configuration options for the program. Here are some of the key settings:

Discord Integration: Enable or disable Discord integration and set up Discord webhook URLs. Control what types of server activities to log, such as admin messages, tribe events, and player messages.

Server Configuration: Add, remove, or modify the ARK game servers you want to monitor.

Usage
Start the ARK: Cross-Ark Chat program.
Enter the map tag, server directory information and optional Discord information.
The server directory is the base directory of the server files.
  In ASM, this is the "Installation Location" at the top of the application with the profile information.
    You can copy the path from the window that "Open Server Installation Folder" button opens.
Check the checkbox in the "Enabled" column to start monitoring the server for chat messages.
  Messages from one enabled server will be sent to all of the other enabled servers.
The map tag will be how the application will show other servers which server the source came from.
For example, I've entered VAL in the field for my Valguero map, and the chat message sent to other servers will look like the following:
[VAL] Kris (Kuli): hello world!

License
This project is licensed under the MIT License - see the LICENSE file for details.
