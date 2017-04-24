# Provider 

## MySQL

```lua
local mysql_dbase       = "mysqlnimsoftslm"     
local mysql_dbserver    = "server-name"         
local mysql_user        = "root"         
local mysql_password    = ""                

-- Build connection string (cs)
local cs = "Provider=MySQL;Initial Catalog="..mysql_dbase..";Data Source="..mysql_dbserver..";User ID="..mysql_user..";Password="..mysql_password..";Port=3306"
local rc = database.open (cs,false)
if rc == NIME_OK then
    local rs = database.query ("SELECT * FROM S_QOS_DATA")
    printf ("Number of QoS objects: %d",#rs)
else
    print ("Failed to open database using the provided connection string!")
end

database.close()
```

# SQL Server

```lua
local SQL = database.open("Provider=SQLOLEDB;Initial Catalog="..dbname..";Data Source="..dbsource..";User ID="..dbuser..";Password="..dbpass..";Network Library=dbmssocn;Language=us_english");
```
