# Peeved Penguins Tutorial :penguin:

![Gameplay Gif](./Screenshots/GamePlay.gif)

Congratulations on finishing Hoppy Bunny and Conway's Game of Life! This next tutorial, you will be cloning the most successful iPhone game to date! This version of Angry Birds, called Peeved Penguins, will be a very physics and design heavy tutorial. You will have the opportunity to really tinker with in game physics and manipulate how different bodies interact with one another.

## What you will learn :white_check_mark:
Upon completing this tutorial, you will have learned how to:
- Switch scenes from a main menu to gameplay
- Create a camera to follow game actions
- Utilize the SpriteKit physics engine
- Use Physics Joints to model a catapult's launch
- Load different levels from SKS files
- Use timeline to create character animations
- Make an iPhone and iPad compatible game
- Texture atlas and performance optimization

## Common issues :bug:
- A faulty catapult arm means you should check your physics joints and make sure they are connected both programmatically and in the SKS file
- If a penguin body does not launch properly or cannot knock down the ice blocks, check the penguin's mass and the impulse at which the penguins are launched from the catapult
- The main menu view controller will not show up if the initially launched game scene is not set to be the main scene sks file
- Similarly, remember to programmatically load new levels by calling the level's sks file name
- Remember Hoppy Bunny? Correct collision and contact mask values are still crucial to making sure your game runs correctly and aesthetically

## What you should understand when finished :checkered_flag:
- A Lot of Physics: Static vs. Dynamic, Polygon (Alpha) vs. Round objects, Physics Joints, Physics as Visual Polish, SKPhysics Contact, Tweaking
- Performance: Texture Atlas
- Game Contact: Level Design, Level Transitions
- Game Mechanics: touchesBegan/Moved/Ended methods, Camera node tracker
- Game Polish: Particle effects as visual polish, Sprite frame animations, Sound Effects
- Device Compatibility: iPad compatibility
