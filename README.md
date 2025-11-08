# JesseMcDanielCita417Assignment3
Video Demo Link - https://www.youtube.com/watch?v=OYVDVUsZme8

For this lab, I made a system where enemies spawn in the level when the game starts. I made a spawner that puts enemies in the map one at a time over a few seconds. When the enemies touch the player, the player loses health. I also added some damage cubes in the level that hurt the player if they run into them. I kept track of how many enemies spawned using a number variable called EnemiesSpawned so I can see when all of them are gone. The game has a basic win/lose system: the wave ends when all enemies are defeated, or the player dies if health reaches zero. I didn’t make a fancy HUD, but you can see health going down when damage happens. I also recorded a video of the whole encounter so you can watch it start to finish. This setup is simple, but it shows that spawning, damage, and waves all work together in the level.


# Feature Check List
I made a spawn point that makes enemies appear one by one.

I made a wave manager that counts how many enemies are alive and when to start or stop spawning.

There are win and lose conditions — you win when all enemies are gone, and you lose when your health hits zero.

I added a HUD that shows my health and how many enemies are left.

There’s a health pickup that gives you health back when you touch it.

The arena has a few blocks and walls to make it more fun to run around.

I used two design ideas: enemies spawn in steady waves, and each wave gets a little harder.

# Directions
Use WASD to move and the Mouse to look around.

Use Left Click to shoot.

Run into the red cubes to take damage and test the health system.

Enemies will spawn automatically — try to survive until they’re all gone!

If your health hits zero, the player dies and the game is over.

