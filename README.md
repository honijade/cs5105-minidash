# cs5105n-dashdash

**Student:** Daniel Jade Sanding  
**Course:** Game Development  

---

## Overview
This activity covers setting up the development environment, version control, and the foundational architecture of the Godot Engine. The objective was to configure a clean workflow with Git and build a running "Hello World" 2D scene.

---

## What I Did

### 1. Development & Version Control Setup
* **Godot Engine:** Installed and configured Godot 4 for 2D development.
* **Git Repository:** Initialized a local repository and connected it to GitHub.
* **Godot-Friendly `.gitignore`:** Added standard exclusions for Godot projects (such as `.godot/`, import caches, and editor-specific files) so the repo stays clean.
* **Git LFS (Large File Storage):** Configured Git LFS to handle large binary media assets (sprites, audio, fonts) properly down the line.

### 2. Core Concepts: Nodes & Scenes
* Learned how Godot organizes games into a tree structure composed of **Nodes** and **Scenes**.
* Created a primary 2D scene (`res://main.tscn`) using a root `Node2D`.
* Added a `Label` child node to display the "Hello World" text.
* Configured the Project Settings to set this scene as the default entry point on run (`F5`).

### 3. Game Concept & Genre Selection
* Explored common 2D game formats (Platformer, Runner, Puzzle, Shooter) and selected the core genre direction for the semester project.

---

## Evidence & Screenshots

### 1. Running "Hello World" Scene
*The 2D scene successfully running in the engine preview:*

![Running 2D Scene]![alt text](image-1.png)

### 2. Godot Workspace & Scene Tree
*The editor layout showing the node hierarchy (Node2D -> Label) and Inspector:*

![Godot Editor Setup]![alt text](image-2.png)

### 3. Git & Repository Verification
*Clean status and Git LFS tracking configuration:*

![Git Status]![alt text](image-3.png)

