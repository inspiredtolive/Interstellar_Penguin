# Interstellar_Penguin
Interstellar_Penguin is a low-poly penguin simulation game made in Unreal Engine 4.24.2.

# Screenshots
![Papa Penguin and baby penguin watching the sunset](https://i.imgur.com/w21h8B8.jpg)
![Papa Penguin and baby penguin being chased by a shark](https://i.imgur.com/SxIvGqh.jpg)

# System Requirements

As of right now, the game only supports Windows 32-bit, Windows 64-bit, and Linux.

To open our project in UE4, recommended specs are:

* Windows 10 64-bit
* Quad-core Intel or AMD, 2.5 GHz or faster
* 8 GB RAM
* DirectX 11 or DirectX 12 compatible graphics card

# Installation

Just head over to [releases] (https://github.com/inspiredtolive/Interstellar_Penguin/releases) and download the latest release. No installation steps are required.

# Features

## Penguin Movement

The Penguin can move on land, swim on the surface of the water and underwater. Use this to capture the fishes!

## Enemy Shark

Make sure to avoid the shark or be prepared to be eaten because the shark will chase you!

## Schooling Behavior For Fishes

The 3 behaviors for flocking/schooling were implemented.
* Cohesion
* Alignment
* Separation

## Obstacle Avoidance

Using a nice irrational number, phi, I plotted points in a sphere spiralling from the direction of fish.
The fish will RayCast to detect if they are heading towards an obstacle. Then it will RayCast in a spiral until it finds a direction that does not collide with the obstacle and head towards that direction.
