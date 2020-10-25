# UnrealHW1
3D Platformer

**Concept**

* ***Platform***: Windows
* ***Technologies***: Unreal Engine 4.24.3, Blueprints
* ***Language***: English
* ***Audience***:  Targeted audience
* ***Genre***: 3D Platformer
* ***Mood***: Calm, positive
* ***Emotions***: 
* ***Rating***:  PEGI 3
* ***User Number***:  Singleplayer
* ***Gameplay time***: 10 min+
* ***Main mechanic***: Endlessly run forward as far as you can
* ***Goal***: Achieve a high score
 
**Targeted audience**

Targeted primarily at casual players who prefer to play simple games in order to kill time.

**Game Character**

Game mechanics and operating
Controls:
  *	Actor moving: WASD keys (W - forward, A - sideways (left), S - backwards, D - sideways (right))
  *	Camera/Rotation: Mouse (move mouse to turn the camera)
  *	Jumping: Spacebar (hold to jump higher)
Game mechanics:
  *	Player can pick up bonuses (coins) in order to get a higher score
  *	Player must avoid falling and bumping into obstacles
  *	Picking up boosts makes it easier to proceed forward (highlighted in order to stand out)
 
**Interface**

HUD:
  *	Score counter

**Gameplay map**
Character spawns at the beginning of the pass with various obstacles
According to user input character can perform movements
Upon falling or colliding with a copper object game restarts (game over)
Collecting bonuses changes game conditions for a set amount of time:
  *	Invincibility bonus allows character to go through copper objects 
  *	Slow bonus slows down moving objects 

**Visual** 

![Game visuals](/screenshot.png)
All the assets were taken from Unreal Engine 4 Starter Contentment Pack.

**Level Design**

Player spawns on a procedurally generated endless path with obstacles.
Player has a score of 0.
In front of the player randomly spawn platforms with moving obstacles, bonuses, boosters, walls and gaps.
Two types of boosters can be spawned: invincibility (allows to go through walls) and slow (slows all moving objects).

**Balance**

  *	Player speed: 800
  *	Player jump max height: 300
  *	Gravity effect on player: x2
  *	Obstacle movement speed: 2 – 5.75 points per event tick (+0.75 per difficulty level)
  *	Slow boost obstacle stalling: 1 point per boost
  *	Invincibility boost time: 8 – 3 (-1 per difficulty level)
  *	Slow boost time: 12 - 4.5 (invincibility boost time x1.5)
  *	Bonuses per platform: 0 – 2 (randomized)
  *	Points per bonus: 10
  *	Difficulty increase on points count: 100/200/400/800/1600
  *	Platform variation proportions: 
    *	Tile with/without wall at the end: 1/3
    *	Tile with/without gap at the end: 1/2
    *	Tile with boost/obstacle/nothing: 1/4/5



