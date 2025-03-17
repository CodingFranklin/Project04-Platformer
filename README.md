# Project04-Platformer
The purpose of this project is to create a 2D platformer game.
2025.3.16

Description
This project will be a simple 2D platformer game that will have a character that can move left and right (controlled by the keyboard) and jump. 
It will also include enemies, platforms, and objects with which you can interact. The camera will follow the player.

## Implementation
_Attack system:_
I added a feature that the player can attack by left-clicking. I first made the animation for it. Then I added an invisible 2D square to be the player's child which is the attack zone. So whenever enemies have triggered the attack zone, they will die.

_Health system:_
The player will at most have 3 health, shown on the left-up corner of the screen. If the player collides with enemies, the player will lose one health. There are some hearts on the map that help the player to recover.

_Background Music:_
Different music for the Start scene, Lose scene, and Win scene.

_Two kinds of enemies:_
(1) RunningEnemy: It initially just looking around for the target, the player, in the range of 4. It will turn around every 4 seconds. When they find the target, they will run towards it. If the target continuously stays in the range, they will keep running. After losing their target, they will stop after 2 seconds.
(2) JumpingEnemy: It will just constantly jump.
Both enemies will die and drop a diamond by one attack.

_Animations:_
I spend most of my time on the animations. I tried to make the player's die animation and it works in level 1 and 2, but weirdly not in level 3. Also, there might be bugs in the transition between the player's Idle and Walk, because the player will turn white for a few frames and I don't know why. Other than the issue above, the animations are good. For example, the door opening, the enemy dying, the player dying ...

## References
Kings And Pigs Assets: https://pixelfrog-assets.itch.io/kings-and-pigs

Pixel Font: https://www.fontspace.com/hachicro-undertale-font-f83280

Pixel Musics: https://pixabay.com/

## Future Development
To be continued...

## Created by
Franklin Pu
