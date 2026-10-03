BOUNCE CLASSIC

Bounce Classic is a retro-inspired arcade game built in pure C using the lightweight Raylib graphics library. Guide the bouncing ball through platforms, avoid hazards, and survive as long as possible.

PROJECT OVERVIEW

This project is a recreation of the classic bounce game concept, written from scratch in C for optimal performance and simplicity. It relies on the Raylib library to handle window management, rendering, and input handling efficiently.

PREREQUISITES

To compile and run this game from the submitted ZIP archive, you will need:

1. C Compiler: A standard C compiler such as GCC (e.g., MinGW-w64 for Windows, or native GCC on Linux/macOS).
2. Raylib Library: The Raylib development libraries installed on your system.

INSTALLING RAYLIB

* Windows (MinGW): Download the Raylib developer package from the official website and configure your include/lib paths, or use an IDE setup like W64devkit or the Raylib starter kit.
* Linux: Install via package manager (e.g., sudo apt install libraylib-dev) or build from source.
* macOS: Install via Homebrew (brew install raylib).

HOW TO COMPILE AND RUN

Extract the contents of the submitted ZIP file into a working directory. Open your terminal or command prompt inside that folder and use the following compilation commands based on your platform:

For Linux / macOS (GCC):
gcc main.c -o bounce_game -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
./bounce_game

For Windows (MinGW):
gcc main.c -o bounce_game.exe -lraylib -lopengl32 -lgdi32 -lwinmm
./bounce_game.exe

PROJECT STRUCTURE

├── main.c          # Main game loop, physics, rendering, and logic
├── assets/         # Sprites, textures, and sound effects (if applicable)
└── README.txt      # Project documentation

CONTROLS

* Left / Right Arrow Keys: Move the ball horizontally
* Spacebar : Jump / Bounce
* ESC: Exit the game
