# Lua-codebase
CA - UIM - Nas LUA Code base

This repository has been created to save many scripts examples for LUA Scripting in NAS.

## Use cases 

- MySQL & MSSQL provider [Here](provider.md)
- Generate alarm (advanced with Spooler callback). [Here](generate_alarm.md)
- Require lua file

## Replace event (example)

```lua
event.message = string.gsub(event.message,"#","/")
event.supp_key = string.gsub(event.supp_key,"#","/")
return event
```

## Script(s) 

- Alarm rafale mode [Git](https://github.com/fraxken/rafale_mode)
- Checkconfig [Git](https://github.com/fraxken/checkconfig_lua)
- Auto-unassign [Git](https://github.com/fraxken/autoalarm_unassign)
