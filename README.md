# WolfAPI BETA
Little BungeeCord API By WolfDev 
documentation

Broadcast message to players with permission
Example:
```javascript
 PlayerAPI.notifyuser("permission","message");
```
Broadcast over to all players
Example:
```javascript
serverAPI.broadcast("message");
```
Kick a Player
Example:
```javascript
ProxiedPlayer player = how you get the player;
PlayerAPI.kickplayer(player, "kick message");
```
