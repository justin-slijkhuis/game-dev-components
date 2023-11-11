# Game dev components

This repository contains code of a learning project called: "Game dev components".

It's purpose is to build a library full of game development components that can be used to build a game.

## Learning

- C#
- Perlin noise
- World generation
- Köppen climate classification
- Component diagram
- Domain model
- Patterns
- SOLID
- GRASP

## Requirements

### World generation

- The world must be able to generate infinitely.
- The world must be able to be unique.
- The world must be able to be shared with others using a seed resulting in exactly the same world generation.
- The world must consist of the by developer chosen or given classification/biomes.
- The world must be fluid, so no spontaneous borders or insanely small biomes/structures/attributes.
- The world must be able to contain structures given by the developer.
- Structures must be able to have multiple version with each having a certain chance to spawn.
- The world must be easily configured by passing it percentages of certain aspects and attributes the world must consist of.
- Different types of world generation must be possible (Open world, dungeons, layers, etc.).
- The world must be able to be generated for 2D and 3D games.

### Game rendering

- A new application must open for the game to render (Windows, Linux and Mac).
- The render must easily and quickly be able to change its content.
- Must be able to render 2D and 3D games.

### Game saving

- The game must be able to be saved in JSON format.
- The game must be able to be saved in SQL format.
- The game must be able to be saved in Objects format.

### Game characters

- Developers must be able to easily add new characters (Monster, Animal, Person, etc.)
- Developers must be able to specify behavior of a character (Passive, Aggressive and Neutral).
- Developers must be able to specify the hitbox of a character.
- Developers must be able to specify the skin of a character.
- Developers must be able to specify character stats.
- Developers must be able to add rarity to character stats and skins.

### Player actions

- A player must be able to move around.
- A player must be able to use their inventory and/or hotbar.
- The amount of items in their inventory and hotbar must be able to be customized.
- A player must be able to attack.
- A player must be able to lose health.
- A player must be able to customize their keybinds for certain actions.
- A player must be able to crouch.
- A player must be able to jump.
- Developers must be able to easily create new player actions.

### Game items

- A player must be able to use items.
- Items must be able to be categorized (weapons, healings, buildings, etc.).
- Items must be able to have different rarities.
- Items must be able to be grouped inside a category (assault rifles, shotguns, medkits, etc.).
- Items must be able to contain certain actions on certain keybinds.
- Developers must be able to use default item actions like shoot, aim and heal.
- Developers must be able to easily create their own actions.

### Multiplayer

- The game must be able to be played with others in real time using Peer-to-Peer.
- The game must be able to be played with others in real time using WebSockets.
- Players must be able to send messages to each other when enabled.

### Game generator

- Must be able to generate a .exe to install the game on Windows.
- The installer must create an icon on their PC to start the game.
