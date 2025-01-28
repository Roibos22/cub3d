# cub3d - 3D Maze Explorer

### Table of Contents
1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [Technologies Used](#technologies-used)
4. [Installation Guide](#installation-guide)
5. [Usage](#usage)
6. [Controls](#controls)
7. [Map File Format](#map-file-format)
8. [Acknowledgements](#acknowledgements)

## Project Overview
[cub3D_demo.webm](https://github.com/user-attachments/assets/5d38f6a3-9fe9-42dd-84eb-fab030d2650f)

Cub3d is an immersive 3D maze explorer game developed as part of the 42 school curriculum. This project challenged us to recreate the classic first-person perspective of Wolfenstein 3D using raycasting techniques, pushing the boundaries of graphical programming and algorithmic thinking.

At its core, cub3d transforms a 2D map into a 3D navigable environment, creating an illusion of depth and perspective. Players can traverse through corridors, rooms, and open spaces, all rendered in real-time using the power of mathematical calculations and efficient programming.

We've gone beyond the basic requirements to implement advanced features like a dynamic minimap for enhanced navigation and custom shaders for improved visual effects, elevating the gaming experience to new heights.

This project not only tests coding skills but also demands a deep understanding of graphics rendering, spatial awareness, and optimization techniques. It's a perfect blend of mathematics, physics, and computer science, wrapped in an engaging gaming experience.

## Key Features
- Realistic 3D perspective rendering using advanced raycasting techniques
- Textured walls with unique textures for each cardinal direction
- Smooth player movement and intuitive camera rotation
- Precise collision detection to maintain game integrity
- Dynamic Minimap: A real-time 2D representation of the maze for enhanced navigation
- Custom Shaders: Implemented for improved visual effects and atmosphere
- Optimized performance for smooth gameplay

## Technologies Used
- C programming language for robust and efficient code
- MinilibX graphics library for rendering and window management
- Raycasting algorithms for 3D perspective rendering
- File parsing techniques for map creation and validation
- Custom shader implementation for advanced visual effects

## Installation Guide
### Prerequisites
- linux
- gcc compiler
- Make

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/Roibos22/cub3d.git
   ```
2. Navigate to the project directory:
   ```
   cd cub3d
   ```
3. Compile the project:
   - For the basic version:
     ```
     make
     ```
   - For the version with minimap and shader:
     ```
     make bonus
     ```

## Usage
Run the executable with any map file from the resources folder, for example:
```
./cub3D resources/valid_map_1.cub
```

## Controls
- W/A/S/D: Move the player through the maze
- Left/Right arrow keys: Rotate the camera view
- ESC: Exit the game

## Map File Format
- .cub extension
- Texture paths for North, South, East, and West walls
- Floor and ceiling colors (RGB format)
- Map layout using characters:
  - 0: Empty space
  - 1: Wall
  - N/S/E/W: Player starting position and orientation
 
We've created a test script that checks our 22 custom maps for any possible errors:
```
./map_test.sh
```

## Acknowledgements
- 42 School for providing the challenging project requirements and resources
- The creators of Wolfenstein 3D for the original inspiration
- Raycasting tutorial by [3DSage](https://www.youtube.com/watch?v=gYRrGTC7GtA&t=1s) for invaluable insights
- Special shoutout to my teammate [Jacob](https://github.com/jakobsitory), whose dedication, ideas, and collaborative spirit were fundamental in bringing this project to life.
