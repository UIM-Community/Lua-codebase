# Require

Go into the "scripts" directory in the NAS Folder ( nimsoft/probes/service/nas/scripts ). and create a lib file (with no .lua extension).

Your nas script : 

```lua
lib = require "lib"

lib.echo(); // Print Hello World!
```


Your lib file content : 

```lua
local mymodule = {}

function mymodule.echo()
    print("Hello World!")
end

return mymodule
```
