Prerequisites  
Before you start, ensure you have the following prerequisites:  

A system running Windows (the program is written in C# and intended for Windows use).  

The ARK server must have been ran at least twice for the files to be created.  

Server Admin Logs must be enabled.  
  In ASM, this option is "Enable Server Admin Logs" under Administration.  
  
The network Local IP must be manually entered.  
  In ASM, this option is "Local IP" under Administration.  
  
RCON must be enabled.  
  In ASM, this option is "Enable RCON" under Administration.  

  
Usage  

Start the ARK: Cross-Ark Chat program.  

Enter the map tag, server directory information and optional Discord information.  

The server directory is the base directory of the server files.  
  In ASM, this is the "Installation Location" at the top of the application with the profile information.  
    You can copy the path from the window that "Open Server Installation Folder" button opens.  
    
Check the checkbox in the "Enabled" column to start monitoring the server for chat messages.  
  Messages from one enabled server will be sent to all of the other enabled servers.

If Discord integration is enabled under the Discord settings, it will send the message to the desired channel's
  webhook. The different type of messages are seperated into the following groups: Tribe, player and server/admin.
  To create a webhook, right click on a Discord channel
  
  ![image](https://github.com/Kulisujin/Ark-Survival-Evolved-Cross-Ark-Chat/assets/58023791/577f0541-28f6-4896-9e40-96aca3be6d86)
    
    Click edit, then integrations
    
  ![image](https://github.com/Kulisujin/Ark-Survival-Evolved-Cross-Ark-Chat/assets/58023791/aebf9080-5554-419e-9ad3-7ad05cdbb0b1)
    
    Under webhooks, either create one or edit an existing one
    
  ![image](https://github.com/Kulisujin/Ark-Survival-Evolved-Cross-Ark-Chat/assets/58023791/7f5b4512-dbb6-4e5f-a6ee-41057ccac2ee)
    
    Press the Copy Webhook Url button, and paste into the appropriate Discord webhook field
    
  ![image](https://github.com/Kulisujin/Ark-Survival-Evolved-Cross-Ark-Chat/assets/58023791/472c086a-ff0e-4617-a52c-516a071b6312)
    
  For messages in Discord to be sent to the maps, enabling the Discord bot is required.
    The bot will only need the channel ID of the channel of which we're looking to monitor.
    
  ![image](https://github.com/Kulisujin/Ark-Survival-Evolved-Cross-Ark-Chat/assets/58023791/577f0541-28f6-4896-9e40-96aca3be6d86)
      
    Discord messages will only be sent to the enabled servers if the message sender "@'s" the bot
    
  ![image](https://github.com/Kulisujin/Ark-Survival-Evolved-Cross-Ark-Chat/assets/58023791/117ec912-876e-4d8a-b83f-f012b1d36789)
      
Admins

  To use admin commands or Discord ping an admin from in-game, add the admins to the admin list in the Discord settings.
  
  ![image](https://github.com/Kulisujin/Ark-Survival-Evolved-Cross-Ark-Chat/assets/58023791/1f4bbe6c-8219-44c2-87b7-d2b0323643a0)
  
  The admin column will be the username of the admin. In ARK, sending a message with "@name" will ping the *name* in Discord based on the
    Discord user id.
    To get the user ID, right click on the Discord user, and click copy user ID. paste that into the "Admin ID" column.
    
  ![image](https://github.com/Kulisujin/Ark-Survival-Evolved-Cross-Ark-Chat/assets/58023791/ee5df732-110e-48e3-9f3c-b23e44635cfe)
    
  Admins added to this list will then be allowed to send server commands if the admin channel ID is filled.
  Commands will only work in the channel designated by the Admin Channel ID field, and only the users entered in the admin list.

The map tag will be how the application will show recipients which server the source came from.  
  For example, I've entered VAL in the field for my Valguero map, and the chat message sent to other servers will look like the following:  
  [VAL] Kris (Kuli): hello world!  

  
License  
This project is licensed under the MIT License - see the LICENSE file for details.  
