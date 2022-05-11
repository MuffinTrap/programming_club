# Learn game development with TIC-80

## Introduction
A tutorial for learning the very beginner basics of game programming. The language used is Lua (https://en.wikipedia.org/wiki/Lua_(programming_language)) and the method is the TIC-80 fantasy console (https://tic80.com/). Lua is a very simple and forgiving programming language and TIC-80 is a sort of all-in-one program for creating small games. It contains the editors for code, sprites, sound and music creation. It also provides many useful functions for game development.

Lean all programming things, such as variables, functions, parameters, control structures and data types. Lessons and examples are arranged in a logical order that will give you more knowledge and tools as you progress. Several simple games are also part of the tutorial.

The tutorial is broken down to levels:
### Level 1
This level covers the fundamental concepts needed to write a small interactive program and teaches how to make custom functions and different uses of variables.

Covered topics: Variables: numbers, booleans. Calling functions, function parameters. If and else. Clearing the screen and drawing, simple input and cursor position detection.

### Level 2
This level adds tools to handle arbitrary number of objects and managing their state.

Covered topics: for-loops, creating and accessing arrays and objects, object state, measuring time.

### Level 3
After this level it is possible to start making a simple game such as Asteroids, Lunar Lander, Space War, Gorillas, Breakout, Snake etc.

Covered topics: simple physics calculations for speed and acceleration, simple collision detection, game loop and game states, drawing sprites, playing sounds.

### Level 4
This level gives high level concepts that enable making more complex games with simple AI such as Gauntlet, Galaxia, Donkey Kong, Tetris etc.

Covered topics: Simple AI, level generation, complex collision to environment, graphical effects, score counting.

## TIC-80 quick quide
* Download from the official site: https://tic80.com/create
* Extract to a nice folder like Documents/TIC80
* Launch the program
* Type '''NEW''' to create a new default cart
* Press '''ESC''' to change between editor and command line. Press '''F1-F4''' to change between editor tabs
* Run the cart with '''Ctrl + R''' and stop with '''ESC'''
* Save by typing '''SAVE cart-name''' where cart-name is the name you want
* See all saved carts by typing '''SURF'''
* The TIC-80 stores the carts/files in C:\Users\'''You'''\AppData\Roaming\com.nesbox.tic\TIC-80  aka, %appdata%\com.nesbox.tic\TIC-80

## How to use this tutorial

The lessons are collected in the Wiki. Each lesson consists of an explanation, some example code and one or more exercises.

* Read the description
* Read the example and try to understand what happens on each line
* Open TIC-80 and type in the example yourself, testing after every change. This way you build a mental connection between code and the result on the screen. Do not copy and paste!
* Try to modify or extend the example yourself.
* Try to break the example intentionally, see what error message you get.
* Read the exercise
* Write or draw a plan on paper or type it. Break down the task into smaller parts that are in a logic succession.
* Start writing the solution bit by bit, testing after changes using trace() and exit()
* Have fun! Experiment!
