# Lua-codebase
CA - UIM - Nas LUA Code base

This repository has been created to save many scripts examples for LUA Scripting in NAS.

-> [Official NAS Lua API](https://docops.ca.com/ca-unified-infrastructure-management-probes/ga/en/alphabetical-probe-articles/nas-alarm-server/the-nas-extensions-to-lua-all-versions)

## Use cases 

- MySQL & MSSQL provider [Here](provider.md)
- Generate alarm (advanced with Spooler callback). [Here](generate_alarm.md)
- Require lua file [Here](require.md)
- Delete old QOS [Here](delete_qos.md)

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

## Community links 

- Lua optimization [Link](https://communities.ca.com/docs/DOC-231173416)
