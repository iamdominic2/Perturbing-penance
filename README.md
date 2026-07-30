# Perturbing Penance

This is a traditional roguelike game.
1. Tile-based movement and turn-based combat.
2. You'll have to restart the game if you die.
The game pushes you in the direction of growing as a player, rather than grinding like a traditional RPG.

BASICS
EXPEIEINCE
You earn experience when you defeat monsters in any way. When you get enough you will level up.
FULLNESS
You have a fullness gauge, and takes 1 damage per turn once it reaches 0. Fullness decreases by 1 every 4 turns, so eat food to replenish fullness.
HP REGENERATION
HP regenerates by 1.33% of your maximum HP each turn.  
USE ITEMS
By openning your inventory with I or C, you can use items you picked up. Select an item with Z to use it, put it on the ground, or view information about the item. 

MAP INTERPRETATION
@ - you
A-Z - monster initial
. - floor
= - wall
o - item
% - stairs
TIPS
Firstly, expect the worst. Don't rely on a direct attack when you are 1 attack from dying.
Draw enemies closer by stepping in place so that you get the first hit.
Go in a coridor to fight enemies 1-on-1.
Act before the situatuion becomes dire by using items.
And don't be in a rush- this isn't an action game!

CONTROLS
Arrow keys to move (You can move diagonally, and through corners)
Z to attack (face an enemy with D before attacking! you can attack through corners)
X+Z to step in place (hp still regenerates)
I or C to open/close inventory
X to exit out of inventory selection menu (when you select an item) or move without picking up items
D+arrow to turn without moving
S to force diagonal movement
M to show/hide minimap
Q to focus minimap
R to retry upon death (or after you beat it, if you want to grow as a player even more)

STATUS CONDITIONS
Confusion- Movement or attack goes in a random direction. Items are unaffected.
Sleep - Unable to perform any actions.
Slow - Move once every 2 turns. 
Paralyzed - Can't move until taking damage.
Buffed - do 50% more damage. Stacks.

## Notes

*THIS IS A NEWER VERSION (with beautiful graphics) of one of my slightly older projects, Procedural Penance. That project is here: https://github.com/iamdominic2/Procedural-Penance-ASCII-type-Roguelike*

*(By the way, over the passage of time, the term "roguelike" has started to lose its original meaning of procedural dungeon crawling, for a more general term for "games that annoy you", but this game is more similar to Rogue itself, luckily without item identification.)*
Monsters:
Ant (1-2F): Weakling
Hen (1-3F): Weak, but double speed
Onigirighost (3-4F): Drains saturation
Zombie (3-5F): Rots food
Snake (4-7F): Paralysis bite
Vampire (5-8F): HP drain
Firepuff (6-11F): Mini fire breath
Nuancer (7-11F): Morphing breath to 1 item
Bee (8-11F): Strong fatal confusion sting
Leecher (12-15F): Strength drain
Yawner (12-15F): Cause sleep
Will-O-Wisp(12-16F): Drain level
Immunacrab(14-17F,26F): Immediate recovery from status
Cursister (16-21F): Curse and destroy 1 item
Reaper (17-25F): Strong double speed
Tiger (19-25F): Throws you somewhere
Punisher (22-29F): Critical axe swing
Eyeball (23-25F, 27-28F): Confusion glare
Queen Idol (26F): Mid boss
Jolteodon (27-36F): Slow but lightning
Mage (28-35F): Sleep or confusion staff
UFO (31-36F): High defense but low HP
Killer (33-39F): Highest attack power
Xplodetank (34-38F): Ranged cannonball
Dragon (35-40F): Floor-wide fire breath
*SUDO GOD*(40F): Final boss