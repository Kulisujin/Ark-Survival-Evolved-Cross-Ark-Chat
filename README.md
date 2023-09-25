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

‎
  
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
