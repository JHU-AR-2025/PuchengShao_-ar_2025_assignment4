# Assignment 4 – Introduction to Augmented Reality (EN.601.654 / EN.601.454)

**Author:** Pucheng Shao
---

## Overview

This repository contains my solutions for **Assignment 4** of *Introduction to Augmented Reality* (Fall 2025).  
It includes:
- **Q2:** Python implementation of the Kalman Filter for pose estimation  
- **Q3:** Unity project implementing an AR-style interactive game (Roll-a-Ball extension)

---

## Folder Structure

Assignment4/Q2/ # Python Kalman Filter
Assignment4/Q2/Q2e.py # Standard Kalman Filter (prediction + correction)
Assignment4/Q2/Q2f.py # Kalman Filter without measurements (prediction only)
Assignment4/Q3/ # Unity project
Assignment4/Q3/Assets/ # Game assets, models, and scripts
Assignment4/Q3/ProjectSettings/ # Unity project configuration
Assignment4/Q3/.gitignore # Standard Unity .gitignore
Assignment4/Q3/Q3.sln # Unity solution file
Assignment4/README.md # This file

## How to Run

### **Q2 – Kalman Filter (Python)**
1. Navigate to the `Q2` folder.
2. Run either file:
   python Q2e.py
   python Q2f.py
The scripts will plot estimated vs. true position/velocity using random noise simulation.

Q3 – Unity Game
Open the Q3 folder as a Unity project

Press Play in the editor to start the demo.

Features:

Start button to begin the game

Player controlled by keyboard (WASD / Arrow keys)

Jump with Spacebar to collect elevated cubes

Power-up capsule appears after collecting all cubes

Power-up enables breaking a wall and reaching the goal

Displays “You Win!” upon success
