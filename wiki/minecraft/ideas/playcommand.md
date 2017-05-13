---
stub: true
title: Play Command Idea
comments: wiki/minecraft/ideas/playcommand
---
### Usage

1. /play with <player>
  - As soon as the player accepts:
    - Should immediately teleport you to that player (or nearby) and allow you the opportunity to play with them as soon as possible.
  - If you are going to survival, your inventory will be set to a unique one specific to when you play with that player.
    - Some abuses may include using this to double ones' inventory, but we'll address those issues with changes to the mechanics to help.
  - If you are going to adventure or a PvP arena, you may be forced to spectate for a time.
    - Some maps may address this by providing creative points for new members to join in the action.
    - E.g. controlling mobs/zombies/or being the opposition (instead of using AI)
  - If you are going to a custom server, it depends if the owner has whitelisted you, and what their rules are for joining in.
    - They will be able to set it to behave like any setting here; regardles of game mode.
  - If you are going to creative/lobby, s'all good.
  - If the player you are teleporting to decides to do so they can choose whether to never, temporarily, or always provide you with their level of build access.
    - This is for convenience and will automatically deactivate if you block, ignore, etc that player.
    - It's mostly so you don't have to override settings for regions, and since teleporting out will cancel their session with you.
    - However if YOU teleport, they will be instructed to teleport with you to continue their session.
      - If you have not granted the player permission to use your permissions and play with you while you're out of range, and if they were in an area they would've otherwise had to walk to to get to (e.g. /tp would've denied them), they will be teleported out of that area back into the previous place they were.
      
2. /play creative
  - Should immediately teleport you to your most recent creative world/region you can currently build in on the main creative server.
  - If none are available then you don't have your first, so your first one will be immediately created, and you will be teleported to the center of it.
  
3. /play survival
  - Should immediately teleport you to your survival character's previous location on the main survival server.
  - If you have never played before, you will be teleported to where your region will be in spectate mode flying high above.
  - You will be instructed to fly around a bit to see if you like the area.
  - You will be able to jump to the next region if you dislike that spot.
  - If you like that spot you can type /claim (or something like it) and your spawn will be set at ground level there, at which point you will be teleported to that point in survival mode ready to play.
  
4. /play adventure
  - You will be immediately assigned a random instance of any adventure map.
  - Since adventure is its own topic, once you're in, you can configure/party/or just play.
  
