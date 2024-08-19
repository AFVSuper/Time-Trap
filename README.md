# Time Trap
Time Trap adds a survival gamemode where you have limited time to play that can be increased using minerals, killing other players or trading with them.

This datapack is an update from the original idea in the 1.8 map [TimeTrap](https://www.planetminecraft.com/project/timetrap---bybrutec/) created by byBrutec.

## Mineral Blocks
To increment the timer, you have to craft mineral blocks, and stand still over one to consume it.

By default the time values are:

- Iron Block: 10min
- Emerald Block: 15min
- Gold Block: 20min
- Diamond Block: 30min
- Netherite Block: 2h

This is configurable in creative with a GUI using the command:
``
/trigger Configuration
``

## Death and PVP
If a player dies, their time is reduced to half the time they had.
If the player is killed by another player, the assassin steals that time.

## Transfer
With the command ``/trigger Transfer set <seconds>`` you can transfer time to the nearest player. This makes trading items for time posible.

## Out Of Time
If a player runs out of time, they can not play and will go into spectator mode.
