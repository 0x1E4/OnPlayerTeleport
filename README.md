# OnPlayerTeleport
This include detects a player who uses Teleport hacks, you can do what ever you want underneath OnPlayerTeleport callback, OnPlayerTeleport is called when the include detects a player use teleport hack also can detect if player using fly hack or airbreak.

## Example

```
public OnPlayerTeleport(playerid, type, Float:distance)
{
    switch(type)
    {
         case 1: //On Foot
         {
               SendClientMessage(playerid, -1, "You are banned from server because Teleport Hack (On Foot)");
               Ban(playerid);
         }
         case 2: //On Vehicle
         {
               SendClientMessage(playerid, -1, "You are banned from server because Armour Hack (On Vehicle)");
               Ban(playerid);
         }
     }
     return 1;
 }
 ```
 
 ## Credits
Emmet_ - Original optp.inc  
Y_Less - YSI\y_bit
 
