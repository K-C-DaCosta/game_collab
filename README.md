# A collaborative project (social experminent) 

This repo aims to answer the question:
"Can a group of random anonymous **programmers** of variable skillset manage to build something together?"

Because most of the people who see this repo will likely have little to no experience with writing software of this nature,I fully expect this project to crash and burn if I start with something too ambitious so Im trying to keep the scope of this project small (but not too small) to start. The people viewing this may not even know git or have **ANY** experience with languages like C/C++/golang/Rust. Game programming is a multi-diciplinary activity which a newbie may not have. This phase is to help weaker programmers participate and gain something.  

# Phase 1 - start with something simple

## Objective
In this phase, you will familairize yourself with git,github

To test the waters, we will build something extremely simple: a single player 2D retro platformer (think something like mario/metroid).
- it will have 5-10 levels
- a menu
- music
- a boss fight at the last level

Remember: we are just bulding a game.
The art,game design,the story are being put in the backseat for this. 

## The catch
is that we'll be doing everything without an Engine. This project will be focused on the programming aspect of game development, artists are welcome tho. The game will be written from the ground up in Rust.
We'll be using openGL for all things graphics related. For audio, we'll be doing all mixing and audio processing ourselves. 
The solution for state management is , again, handled by US and is going to be something WE implement ourselves.

## Why rust? 
I'm chosing rust because:
- if you already know C/C++ it should be easy to get into
- outputs reasonably fast machine code, so its good for applications like this
- has a strong but simple type system
- documentation uses markdown so no need to learn new syntax for that there
- has built in testing infastructure
- has a good module system
- has good wasm support ( its easier to cross compile projects to wasm than using other languages )
- has good error messages 
- newer programmers will be prevented from adding obvious bugs to the code base, thanks to the borrow checker


# Phase 2 - do something complicated 

A more ambitious project (a 3D, multiplayer game )  
