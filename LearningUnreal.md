# Learning Unreal Engine Game Development
#### by Joanna Lee
---
# Preface
Unreal Engine helps you make awesome games. It's free now! Get it!

---
# Chapter 1: An Overview of Unreal Engine
- What goes into a game?
    - try visualizing and breaking any game down into its fundamental components
    - this will help with designing a game level
    - FPS shooter (mouse click, shoots gun, particle effect and sound (gun and bullet hitting the target)
- What is a game engine?
    - provides you with tools and programs to help you customize and build a game
    - Unreal Engine is a popular choice
- History of Unreal Engine
    - general overview of the history of Unreal
- Game Development
    - Game production stages
        - preproduction/planning, production stage, postproduction stage
        - most time spent in production
    - iterative process involving level prototypes to be created and tested to see if game is viable
    - consists of artists (2D/3D modeler, animator), cinematic creators, sound designers, game designers, and programmers
- The components of Unreal Engine 4
    - Sound engine
        - allows you to play various sound files to set the mood and add realism to the game (ambient noise, triggered sounds)
    - Physics engine (PhysX engine)
        - allow objects to act similarily to real life using programming
    - Graphics engine 
        - responsible for the output on your display by taking in information about the entire scene
        - power of a graphics engine affects how realistic your scene will look
        - Unreal is capable of photorealitic quality
        - supports DirectX 11/12, OpenGL, and JavaScript/WebGL rendering
    - Input and gameplay framework
        - Unreal Engine consists of an input system that converts key and button presses by the player into actions performed by the in-game character
        - input system can be configured through the **Gameplay framework**
            - contains the functionality to track game progress and control the rules of the game
            - Gameplay classes such as GameMode, GameState, and PlayerState set the rules and control the state of the game
            - with the Unreal Gameplay framework and controllers in place, it allows for full customization of the player’s behavior and flexibility
    - Light and shadow
        - UE provides a set of basic lights: Directional Light, Point Light, Spot Light, and Sky Light
        - effective design of light also creates realistic shadows for your game
        - two types of shadows: static and dynamic


---
# Vocab list
- particle effect - disply of sparks, smoke, crumbling wall to show interaction
- UE - Unreal Engine abbreviated
- non-player characters (NPCs) aka bots - (players that are controlled by the
computer through artificial intelligence)
- Kismet - visual scripting system
- MMOG - massively multiplayer online game
- Blueprint - scripting system replacing Kismet
- Sound Cue - triggering of the sounds is implemented through cues
- Heads-up displays (HUDs)/user interfaces (UIs) - part of the Gameplay framework to provide feedback to the player during the course of the game
- Pawn class - In-game characters, whether controlled by the player or AI
- Character class - subset of the Pawn class, which is specifically made for vertically-oriented player representation (humans)
- Directional Light - emits beams of parallel lights
- Point Light - emits light like a light bulb (from a single point radially outward in all directions)
- Spot Light - emits light in a conical shape outwards
- Sky Light - mimics light from the sky downwards on the objects in the level
- Static shadows - can be prebaked into the scene which makes them quick to render
- Dynamic shadows - changed during runtime and are more expensive to render
