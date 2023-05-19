---
layout: post
title: "2D Platform Game Project"
subtitle: "Game Prototype"
date: 2023-01-10 00:00:00 -0400
background: '/img/portfolio/2DGamePlattformProject/2D-Game-Platform-Project.JPG'
icon: '/gif/2D-Platform-Game/RobotPlayer.gif'
---

# About the game

This is a prototype of a 2D platform and action videogame where we will control a robot in a stage surrounded by enemies and other elements to interact with.

<img src="/gif/2D-Platform-Game/RobotPlayer.gif" alt="img" class="responsive-gif" width="192" height="192"/>

___

# Game mechanics

Here we will talk about each of the elements of the game and how they work.

## Energy bar

This bar indicates more than the life of the robot, its energy.
In addition to enemy attacks, shooting will also reduce our energy.

<img src="/gif/2D-Platform-Game/energyBar.gif" alt="img" class="responsive-img" width="600" height="400"/>

## Collectible coins

These coins will be scattered throughout the stage and will recover the energy bar.

<img src="/gif/2D-Platform-Game/wattCoin.gif" alt="img" class="responsive-gif" width="384" height="64"/>

## Enemies

Throughout the stage we will find other enemy robots, these will move around the stage detecting walls or edges, in which case they will change their direction.

<img src="/gif/2D-Platform-Game/enemyRobotMovement.gif" alt="img" class="responsive-img" width="600" height="400"/>

We will be able to shoot them to defeat them and if they collide with us they will take energy from us.

<img src="/gif/2D-Platform-Game/enemyBot.gif" alt="img" class="responsive-gif" width="128" height="128"/>

## Jumper

These jumpers will help us to reach high areas of the game, jumping on them will propel us through the air.

<img src="/gif/2D-Platform-Game/jumper.gif" alt="img" class="responsive-img" width="600" height="400"/>

## Switches and doors

During the game we will see closed doors, to open them we will need to find a switch of the same color that opens it. 

When we press the E key on a switch, it will trigger an event that opens the door.

<img src="/gif/2D-Platform-Game/switchDoorEvent.gif" alt="img" class="responsive-img" width="600" height="400"/>

## Boxes

We will be able to find boxes in the game that we must drag to solve simple puzzles.

<img src="/gif/2D-Platform-Game/boxPush.gif" alt="img" class="responsive-img" width="600" height="400"/>

## Door teleporter

These doors will take us to other parts of the stage.

<img src="/gif/2D-Platform-Game/doorTeleport.gif" alt="img" class="responsive-img" width="600" height="400"/>

## Grappling hook

At certain points in the game we can grab and swing with a hook.

Using the E key when we are close to these grip points will create a link with our character, when we press the E key again we will be impulsed.

<img src="/gif/2D-Platform-Game/grapplingHook.gif" alt="img" class="responsive-img" width="600" height="400"/>


___

# Other game features

## Parallax Background

To add more depth to the background, a Parallax Background has been implemented with several layers that move relative to the camera movement at different speeds.

<img src="/gif/2D-Platform-Game/parallaxBackground.gif" alt="img" class="responsive-img" width="600" height="400"/>

## Projectile pooling

To avoid slowing down the game, a pooling technique has been implemented for the robot's projectiles.
The game will create more instances of the bullet on demand.

<img src="/gif/2D-Platform-Game/projectilePooling.gif" alt="img" class="responsive-img" width="600" height="400"/>


___

### Try it out on Itch.io


<iframe frameborder="0" class="responsive-gif" src="https://itch.io/embed/1951219?border_width=3&amp;bg_color=afbfff&amp;fg_color=880e4f&amp;link_color=f4511e&amp;border_color=6a1b9a" width="556" height="171"><a href="https://sergiogg.itch.io/2d-plattform-game-prototype">2D Plattform Game Prototype by SergioGG</a></iframe>

___

### Other links:

- [Youtube Gameplay](https://youtu.be/UhSLsByS55E)

- [Github Repository](https://github.com/SergioGG96/2D-Platform-Game-Project.git)