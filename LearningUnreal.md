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
    - Post-process effects
        - effects that are added at the end to improve the quality of the scene
        - UE offers full scene high dynamic range rendering (HDRR)
        - UE4 post-process effects include Anti-Aliasing using Temporal Anti-Aliasing (TXAA), Bloom, Color Grading, Depth of Field, Eye Adaptation, Lens Flare, Post Process Materials, Scene Fringe, Screen Space Reflection, and Vignette
        - users are normally given the option to turn them off, if desired because they often consume reasonable amount of additional resources in return for better visuals
    - Artifical intelligence
        - intelligence created by humans to mimic real life
        - humans created AI to give objects a brain, the ability to think, and make decisions on their own
        - made up of complex rule sets that help objects make decisions and perform their designed function/behavior
        - UE4 provides a good basic AI and lays the foundation for you to customize and improve the AI of the NPCs in your game
    - Online and multiplatform capabilities 
        - it also has an online subsystem to provide games the ability to integrate functionalities that are available on Xbox Live, Facebook, Steam, etc
- Unreal Engine and its powerful editors
    - Unreal Editor
        - the main editor that allows access to other subsystems, such as the Material and Blueprint subsystems
        - provides a visual interface made up of viewports and windows to enable you to import, organize, edit, and add behaviors/interactions to your game assets
        - other subeditors/subsystems have very specialized functions that allow you to control details of an asset
        - allows physical placement of assets and gives users the ability to control gameplay variables without having to make changes in the code
    - Material editor
        - 
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
- High dynamic range rendering (HDRR) - This allows objects that are bright to be very bright and dark to be very dark, but we are still able to see details in
them
- Temporal Anti-Aliasing (TXAA) 
- Artifical intelligence - intelligence created by humans to mimic real life
- Universal Windows Platform (UWP)


