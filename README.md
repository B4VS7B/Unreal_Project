# Unreal Engine Collision and Sound Project

## Project Overview
This project demonstrates basic collision and sound effects in Unreal Engine using Blueprints. The setup includes spheres that fall onto cubes, triggering destruction of the cubes and playing an explosion sound.

## Features
- **Collision Detection**: When a sphere hits a cube, it triggers a destruction sequence for the cube.
- **Sound Effect**: Plays a 2D explosion sound upon cube destruction for added immersion.
- **Blueprint Logic**: Utilizes Unreal's Blueprint system to handle collision detection, actor destruction, and sound playback.

## Blueprint Setup
The main Blueprint logic includes:
1. **Event Hit**: Detects when a sphere collides with a cube.
2. **Actor Has Tag**: Checks if the collided actor has the "Destroy" tag before proceeding.
3. **Play Sound 2D**: Plays an explosion sound when conditions are met.
4. **Destroy Actor**: Destroys the cube after collision.

## How to Run
1. Add the `Destroy` tag to the cube actors to enable destruction.
2. Start the Unreal project and observe the collision interactions.
3. When the sphere hits the cube, you hear an explosion sound, and the cube will be destroyed.
