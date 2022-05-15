Engine
======

Methods

=============================== =============================== =============================== 
Method                          Arguments                       Return
=============================== =============================== =============================== 
getScreenSize                   nothing                         vector2
getViewAngles                   nothing                         vector3
setViewAngles                   vector3
isInGame                        nothing                         bool
isConnected                     nothing                         bool
isHLTV                          nothing                         bool
getLevelName                    nothing                         string
command                         string (runs console command)
getMaxClients                   nothing                         number
getConvarInt                    string (convar name)            number
getConvarFloat                  string (convar name)            number
setConvarInt                    string , number
setConvarFloat                  string , number
=============================== =============================== =============================== 