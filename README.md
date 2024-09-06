# CS2Rcon  

test 60 temp
!rcon mp_roundtime_defuse 60;mp_roundtime_hostage 60;mp_roundtime 60;mp_restartgame 1
  
This is an implementation of a RCON plugin for CS2 using CounterStrikeSharp  
<https://docs.cssharp.dev/>  
  
Permission to use the RCON plugin can be granted by adding the permission `@css/rcon` to the user in the admins.cfg.  
  
---
# usage:  
| Command   | Parameter          | Description                          | Permissions |
|-----------|--------------------|--------------------------------------|-------------|
| !rconinfo |                    | prints the plugin information        |             |
| !rcon     | <command (string)> | runs server commands from the client | @css/rcon   |
  
---
# installation:  
Extract the `addons` folder to the `/csgo/` directory of the dedicated server.  
