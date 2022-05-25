# AFKer
A tera-proxy module that prevents you from getting back to the character select screen.  
Once activated, the server's AFK check will not kick you out of the game.  

## Usage
The script is enabled by default and will prevent you from getting logged out when you are standing still for an hour.  
Simply moving your character will reset the 1 hour timer and make you able to go back to character selection.  
  
While in game, open a proxy chat session by typing "/proxy" or "/8" in chat and hitting the space bar.  
This serves as the script's command interface.  
The following commands are supported:  
  
* **afk** - enable/disable AFKer

## Safety
Whatever you send to the proxy chat in game is intercepted client-side. The chat is NOT sent to the server.  

## Changelog
<details>

### 1.2.6
* [~] Look and feel will now be the same on Caali's and Pinkie's proxy
### 1.2.5
* [~] Code changes due to Caali's recent tera-proxy updates
* [-] Removed support for Pinkie Pie's tera-proxy
### 1.2.4
* [*] Fixed a weird case-sensitivity issue
### 1.2.3
* [+] You won't be logged out anymore when other players or NPCs move you (thanks to Owyn)
* [+] Now supports auto-updating via Caali's tera-proxy
### 1.2.2
* [*] Updated hook versions for compatibility with the latest tera-proxy
### 1.2.1
* [*] Some code cleanup
* [*] Full conversion to Pinkie Pie's command module
### 1.2.0
* [+] AFKer will now activate itself after standing still for an hour
* [*] AFKer is now enabled by default
* [+] Added support for Pinkie Pie's command module which is now a requirement
### 1.1.0
* [+] Added !afk command to toggle between "on" and "off" in non-whisper chats
### 1.0.0
* [~] Initial Release

</details>