# Ynnos the Ekamer
Ynnos the Ekamer is a challenging turn-based RPG game that is inspired by the Flash games Sonny and Sonny 2. Made in Unity, the objective of the game is to fight through stages of battles that test your strategic skills, in order to further an exciting story. To do this, you will level-up your characters, buy better equipment, unlock new abilities and create your own strategies.

The game features maps, different abilities, different enemies and different items.

Will you be a fiery attacker, preferring offense over defense? Will you prioritize defenses, bulldozing your way through any attack? Or will you focus debilitating your enemies, weakening them until they pose no threat at all? You decide!

# KTH Project Course II1305
This project was created for the course **II1305 - Project in Information and Communication Technology**. It is done in Unity with the help of 8 team members together in the team **Decisiontree**. You can find more information about the project and the team on [Our Website](https://decisiontree.se).

---

## 🎯 Project Overview

**Course:** II1305 – Project in Information and Communication Technology  
**Institution:** KTH Royal Institute of Technology  
**Project Type:** Game development using Unity (C#)   

The main objective of the project was to:
- Design and implement a small but fully functional **narrative-based RPG game**.
- Integrate **decision tree logic** to control combat, story progression, and player choices.
- Apply **object-oriented programming**, **team collaboration tools (Git)**, and **Agile methods**.
- Demonstrate a complete **software development lifecycle** (requirements → design → implementation → testing → delivery).

---

## 🧩 Game Concept

The game is a **turn-based RPG** where the player interacts with enemies, items, and skills in combat.  
A **decision tree system** determines enemy behavior and player outcomes based on attributes, stats, and chosen actions.

**Key features:**
- Player and enemy combat system  
- Multiple combat scenes and cutscenes  
- Inventory and skill management system  
- Health and mana bar components  
- Audio effects and sprite-based animations  
- Dynamic difficulty adjustment using decision tree logic  
- Victory/defeat screens and in-game menus  

---

## 🏗️ Technical Stack

- **Game Engine:** Unity  
- **Language:** C#  
- **Version Control:** Git & GitHub  
- **Assets:** Custom and open-source 2D sprites, sounds, and animations  
- **Render Pipeline:** Universal Render Pipeline (URP)  

---

## 🕹️ Game Features

### 🔸 Combat System
- Turn-based combat logic.
- Enemies make decisions based on a **decision tree AI**, evaluating conditions like health, distance, and player status.
- Skills include attacks, heals, shields, and special abilities (e.g., mind control, heat wave).

### 🔸 Decision Tree Logic
Implemented to make the game’s AI feel dynamic and adaptive:
- Branches based on health thresholds, player proximity, and available mana.
- Encoded as C# logic within Unity scripts.

### 🔸 User Interface
- HUD with health and mana bars (`HealthBar.prefab`, `ManaBar.prefab`).
- In-game menu, store, and skill tree screens.
- Win/Lose conditions displayed with visual feedback.

### 🔸 Audio and Visual Design
- 2D sprites and animations for player and enemies.
- Layered background and particle effects.
- Sound effects for every major interaction (attack, heal, death, etc.).
- Background music for combat and exploration scenes.
