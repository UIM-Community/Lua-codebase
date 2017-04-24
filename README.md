# Lua-codebase
CA - UIM - Nas LUA Code base

This repository has been created to save many scripts examples for LUA Scripting in NAS.

## Scripts 

- MySQL & MSSQL provider [Here](provider.md)
- Generate alarm (advanced with Spooler callback). [Here](generate_alarm.md)
- Require lua file

## Replace event (example)

```lua
event.message = string.gsub(event.message,"#","/")
event.supp_key = string.gsub(event.supp_key,"#","/")
return event
```
