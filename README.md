# walkLeftToRight
walkLeftToRight turns your game object into an enemy who walks around and stops the player.

# Functionalities
There are a couple of functionalities that are all customizable by the user. 
The functionalities are:

-   Being able to turn the aggressiveness of the enemy on or off (ability to stop the player).
-   Ability to set the walking speed of the enemy.
-   Ability to set the start and end points of the distance the enemy has to walk.
-   Ability to set the sprites for walking to the left and walking to the right.

# Installation
To use this script there are a couple of steps to be done first. The following steps are to be followed to set up the basic use of the script.
1. Place the cs file in the scripts folder of your project.
2. Create a new game object or select an enemy you have already created.
3. Add a new component to the game object and select walkLeftToRight.
4. Fill in the properties of the script in the inspector.

These are the basics of the script, if you only want your game object to walk around you are finished setting up. if you want your enemy to be able to stop the user follow these next steps.
1. Select the box "Aggressive" in the inspector.
2. Add the tag "Protagonist" to your player (Note, this action is done to the player *NOT* to the enemy game object).
3. Make sure the class of your *Player* which defines it's movement is called "Movement" and you have added a Boolean called "Locked" to deactive these controls.
