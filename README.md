#CowBoy Bebop FPS Shooter

**CowBoy BeBop**

Inspired by the Unity 3D tutorial at https://unity3d.com/learn/tutorials/s/survival-shooter-tutorial

## Specifications:

-Built using Unity 3D game engine
-Coded in C#
-Windows and MacOS supported
-Requires a keyboard and mouse to play.
-Requires a graphics card that supports OpenGL 2.1 or higher.4

### Supported Platforms

- MacOS
- Windows PC

### Summary
-Cowboy bebop is Third Person Shooter game in which we are constantly surrounded by different waves of enemies which chip away small damage from the player. 
-We as player are given an automatic rifle to kill the enemies. 
-There are different powerups which we can take from dead enemies to make our gameplay easier. 
-The as of now has no ending it is just a survival game in which you have to survive the maximum number of waves.

## Installation:

**Download the project and follow the steps (based on your OS):**

### Windows

Navigate to _/Builds/Windows_ and run the _.exe_ file to install

### MacOS

Navigate to _/Builds/MacOS_ and run the _.app_ file to install

## Game Menu:
- A game menu with options for controlling brightness, music and effect volumes
- There us data persistence of the volumes so the settings do not have to be set repeatedly
- There are 2 buttons to Start/Resume and Exit
- Can be reached by pressing 'Esc' key to Pause the game

## Player (Character):
- Animated child with running, idle and dying animations
- Has a gun which fires only 1 bullet at a time ...... (initially)
- Moves with movement keys and fires on _Click_ or pressing _Left Ctrl_ key. Pointer to be used for setting firing direction
- Starts with 100 health

## Enemies:
-It has basic 3 types of enemies
- **Zombear:** Can attack when in proximity and runs to player **if** in its line of sight
- **Zombunny:** Functionally similar to _Zombear_, but looks different
- **Hellephant:** Can fly around, attacking with bullets
- Each type has different kill points
- Each has their own set of animations (for idle, moving, dying actions)
- They burn up in flames when killed and drop pickup items randomly

## Waves:

- Fixed set of enemies per wave
- Next wave triggered if all enemies killed or none killed in the last 20 seconds
- After wave 10, the difficulty increases automatically
- With each wave - the number of enemies, enemy health, score points increases

## Pickups:

- Dropped on random when enemies killed
- **Health:** Adds 25 points to health
- **Bounce:** Bullets become green and bounce 4 times when they hit other game objects (30 secs)
- **Pierce:** A single bullet can pierce through enemies but not game objects (20 secs)
- **Extra bullet:** Adds an extra bullet to be fired

## Gameplay:

- Mini map toggle by pressing 'M' key for seeing a wider area of the environment
- Timers showing the time remaining for bounce/pierce pickups to expire
- Health bar in red when health under 30%
- Counters showing current wave, score and enemies alive
