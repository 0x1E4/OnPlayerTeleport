# OnPlayerTeleport
Useful for detecting if player use Health/Armour Hack (99% accurate af)

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
Emmet_ - optp.inc  
Y_Less - YSI\y_bit
 
