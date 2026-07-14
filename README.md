# Death Signal

**Death Signal** is a third-person drone game prototype developed with **Unreal Engine 5**.

The player controls a drone equipped with a flight stabilization system and explores an abandoned and hazardous environment. The objective is to avoid obstacles, navigate through the level, and find the hidden exit.

The project focuses on physics-based drone movement, PID flight stabilization, environmental exploration, and smooth transitions between the main menu and the gameplay level.

## Features

- **PID-Based Drone Stabilization System**
  A PID controller continuously adjusts the drone's orientation, helping it remain stable under gravity, inertia, and external disturbances.
- **Physics-Based Flight Controls**
  The drone is controlled through physical forces and torque rather than directly changing the Actor's position.
- **Independent Altitude and Orientation Controls**
  Horizontal movement, altitude, and facing direction can be controlled independently.
- **Flight Debug Information**
  Players can display lift force, control input, and other flight-related debug information during gameplay.
- **Drone Reset System**
  The drone can be quickly returned to a predefined position if it crashes, becomes stuck, or leaves the playable area.

## Controls

| Key                          | Action                                                     |
| ---------------------------- | ---------------------------------------------------------- |
| `W` / `A` / `S` / `D`        | Move the drone horizontally                                |
| `Up Arrow` / `Down Arrow`    | Move up and down                                           |
| `Left Arrow` / `Right Arrow` | Rotate the drone's facing direction                        |
| `R`                          | Reset the drone's position                                 |
| `F`                          | Show or hide lift force and other flight debug information |
| `Esc`                        | Exit the game                                              |

## Video

[Link](https://www.youtube.com/watch?v=3oFakno3bT4)

