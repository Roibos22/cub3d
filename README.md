# cub3d - 3D Maze Explorer

### Table Of Contents
1. [Project Overview](#project-overview)
2. [Installation Guide](#installation-guide)
3. [Usage](#usage)
4. [Acknowledgements](#acknowledgements)

## Project Overview

cub3d is an immersive 3D maze explorer game developed as part of the 42 school curriculum. This project challenges students to recreate the classic first-person perspective of Wolfenstein 3D using raycasting techniques, pushing the boundaries of graphical programming and algorithmic thinking.
At its core, cub3d transforms a 2D map into a 3D navigable environment, creating an illusion of depth and perspective. Players can traverse through corridors, rooms, and open spaces, all rendered in real-time using the power of mathematical calculations and efficient programming.
This project not only tests coding skills but also demands a deep understanding of graphics rendering, spatial awareness, and optimization techniques. It's a perfect blend of mathematics, physics, and computer science, wrapped in an engaging gaming experience.

### Technologies Used

- C programming language for robust and efficient code
- MinilibX graphics library for rendering and window management
- Raycasting algorithms for 3D perspective rendering
- File parsing techniques for map creation and validation

### Learning Objectives

- Master the implementation of raycasting algorithms for 3D visualization
- Gain proficiency in graphics programming and rendering techniques
- Develop skills in efficient memory management and performance optimization in C
- Learn to parse and validate complex input files for game map creation
- Implement intuitive game logic and smooth player movement controls

## Installation Guide

### Prerequisites

- gcc compiler
- Make
- MinilibX library

### Installation

1. Clone the repository
```
git clone https://github.com/Roibos22/cub3d.git
```
2. Navigate to the project directory
```
cd cub3d
```
3. Compile the project
```
make
```

## Usage
You can now run the executable with a map file from the maps folder:
```
./cub3d maps/example.cub
```

Map File Format
The map file (.cub) should follow this format:

Texture paths for North, South, East, and West walls
Floor and ceiling colors (RGB format)

Map layout using characters:
0: Empty space
1: Wall
N/S/E/W: Player starting position and orientation

### Features

- Realistic 3D perspective rendering using advanced raycasting techniques
- Textured walls with unique textures for each cardinal direction
- Smooth player movement (forward, backward, left, right)
- Intuitive camera rotation for an immersive experience
- Precise collision detection to maintain game integrity
- Optional minimap display for enhanced navigation

### Controls

- W/A/S/D: Move the player through the maze
- Left/Right arrow keys: Rotate the camera view
- ESC: Exit the game

## Acknowledgements

- 42 School for providing the challenging project requirements and resources
- The visionary creators of Wolfenstein 3D for the original inspiration
- Raycasting tutorial by Lode Vandevenne for invaluable insights
- Special shoutout to my teammate Jacob, whose dedication, ideas, and collaborative spirit were fundamental in bringing this project to life.
