# Perturbing Penance

This is a traditional roguelike game.<BR>
1. Tile-based movement and turn-based combat.<BR>
2. You'll have to restart the game if you die.<BR>

The game pushes you in the direction of growing as a player, rather than grinding like a traditional RPG.

## BASICS<BR>
### EXPEIEINCE<BR>
You earn experience when you defeat monsters in any way. When you get enough you will level up.<BR>
### FULLNESS
You have a fullness gauge, and takes 1 damage per turn once it reaches 0. Fullness decreases by 1 every 4 turns, so eat food to replenish fullness.<BR>
### HP REGENERATION
HP regenerates by 1.33% of your maximum HP each turn.  
### USE ITEMS
By openning your inventory with I or C, you can use items you picked up. Select an item with Z to use it, put it on the ground, or view information about the item. 

## MAP INTERPRETATION
Yellow dot - You <BR>
Red dot - Enemy<BR>
Sky blue dot - Item<BR>
Square - Portal<BR>
Blue - Room<BR>
Pink - Hallway

## TIPS
Firstly, expect the worst. Don't rely on a direct attack when you are 1 attack from dying.<BR>
Draw enemies closer by stepping in place so that you get the first hit.<BR>
Go in a corridor to fight enemies 1-on-1.<BR>
Act before the situation becomes dire by using items.<BR>
And don't be in a rush- this isn't an action game!

## CONTROLS
Arrow keys to move (You can move diagonally, and through corners)<BR>
Z to attack (face an enemy with D before attacking! you can attack through corners)<BR>
X+Z to step in place (hp still regenerates)<BR>
I or C to open/close inventory<BR>
X to exit out of inventory selection menu (when you select an item) or move without picking up items<BR>
D+arrow to turn without moving<BR>
S to force diagonal movement<BR>
M to show/hide minimap<BR>
Q to focus minimap<BR>
R to retry upon death (or after you beat it, if you want to grow as a player even more)

## STATUS CONDITIONS
Confusion- Movement or attack goes in a random direction. Items are unaffected.<BR>
Sleep - Unable to perform any actions.<BR>
Slow - Move once every 2 turns. <BR>
Paralyzed - Can't move until taking damage.<BR>
Buffed - do 50% more damage. Stacks.<BR>

## Notes

*THIS IS A NEWER VERSION (with beautiful graphics) of one of my slightly older projects, Procedural Penance. That project is here: https://github.com/iamdominic2/Procedural-Penance-ASCII-type-Roguelike*

*(By the way, over the passage of time, the term "roguelike" has started to lose its original meaning of procedural dungeon crawling, for a more general term for "games that annoy you", but this game is more similar to Rogue itself, luckily without item identification.)*<BR>
## Monsters:
Ant (1-2F): Weakling<BR>
Hen (1-3F): Weak, but double speed<BR>
Onigirighost (3-4F): Drains saturation<BR>
Zombie (3-5F): Rots food<BR>
Snake (4-7F): Paralysis bite<BR>
Vampire (5-8F): HP drain<BR>
Firepuff (6-11F): Mini fire breath<BR>
Nuancer (7-11F): Morphing breath to 1 item<BR>
Bee (8-11F): Strong fatal confusion sting<BR>
Leecher (12-15F): Strength drain<BR>
Yawner (12-15F): Cause sleep<BR>
Will-O-Wisp(12-16F): Drain level<BR>
Immunacrab(14-17F,26F): Immediate recovery from status<BR>
Cursister (16-21F): Curse and destroy 1 item<BR>
Reaper (17-25F): Strong double speed<BR>
Tiger (19-25F): Throws you somewhere<BR>
Punisher (22-29F): Critical axe swing<BR>
Eyeball (23-25F, 27-28F): Confusion glare<BR>
Queen Idol (26F): Mid boss<BR>
Jolteodon (27-36F): Slow but lightning<BR>
Mage (28-35F): Sleep or confusion staff<BR>
UFO (31-36F): High defense but low HP<BR>
Killer (33-39F): Highest attack power<BR>
Xplodetank (34-38F): Ranged cannonball<BR>
Dragon (35-40F): Floor-wide fire breath<BR>
\*SUDO GOD\*(40F): Final boss
