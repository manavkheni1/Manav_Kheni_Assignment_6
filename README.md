# Assignment 6: 2D Animation Implementation

## Overview
This project is a submission for Assignment 6. It demonstrates the implementation of 2D Sprite Animations, 2D Simple Directional Blend Trees, and Frame-by-Frame cycle animations within the Unity Engine.

## Asset Documentation & Attribution
Per the assignment requirements, below is the explicit documentation of original versus borrowed assets and code.

### 🟢 Original Assets (Created by Manav Kheni)
**Art Assets:**
All 2D sprites, sprite sheets, and pixel art were created entirely from scratch for this project using Photopea. No internet-sourced art or AI-generated images were used.
* `DataShard.psd` (Used for the simple Prop Animation)
* `DroneSheet.psd` (Custom 4-directional character sprite sheet)
* `Antigrav_Sheet.psd` (Custom 3-frame VFX cycle)

**Code/Scripts:**
* `DroneController.cs`: **100% original code** written specifically for this assignment to connect player keyboard input (WASD) to the Unity Animator parameters (`DirX`, `DirY`), allowing for live testing of the Blend Tree.

### 🔴 Borrowed / Third-Party Assets
* **Game Engine:** Unity Engine.
* **Systems utilized:** Standard Unity `Animator`, `Animation Layers`, and built-in `Input Manager`. 
* *Note: No external C# libraries, Asset Store plugins, or borrowed code snippets were used in this project.*

## License
**Educational Use Only**
This project was created for educational purposes. The original art assets and scripts provided in this repository are the property of the author. You may review the code and implementation for grading and educational reference, but commercial use or redistribution of the original assets (`.psd` files and custom `.anim` files) without permission is prohibited.

Please see the [EDUCATIONAL USE LICENSE](LICENSE.txt) file for full details and restrictions.
