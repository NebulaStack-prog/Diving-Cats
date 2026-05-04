## **Part 1. Main Document.**

### **1. Title and Basic Information.**

• **Name:** Diving Cats

• **Purpose:** Project No. 5. Product.

• **Project Phase:** Phase I

• **Technology Stack:** Construct 3

• **Project Status:** Fully completed.

### 2. Brief Project Description.

• Diving Cats is an underwater memory game. Two cats swim forward, collecting starfish and avoiding jellyfish.

• When colliding with a jellyfish, one life is lost (there are three in total). The goal is to collect as many stars as possible.

• The characters and background are animated through frame changes. The game has no complex mechanics, but it has something more important: sincerity and warmth.

### 3. Clear Project Goals.

• Create a project that will become a memory.

• Implement simple controls and visually soft graphics.

• Expand the NebulaStack project portfolio.

• Demonstrate the use of Construct 3 as a new tool in the NS ecosystem.

### 4. Project Components.

• **Main characters: cats (Asya and Kuzya).**

• **Enemies:** jellyfish.

• **Objectives:** starfish.

• **Lives:** three hearts in the corner of the screen.

• **Score:** at the top center of the screen.

### 5. User Guide.

• Download the project file from GitHub.

• Open Construct 3 (browser or application) → “Open” → select the downloaded file.

• Launch the game using the “Start” button on the top panel.

• Controls: hold the Space key – movement up and down.

• Construct 3 is required to run the project (the free version is sufficient). There is no ready executable (.exe) file yet.

### 6. Memory and Creation Background.

• **This project differs from others by its main purpose – to create an eternal memory of two cats who passed away and were very dear.**

• **Their names – Asya and Kuzya – will remain within NebulaStack as long as the ecosystem lives.**

• **Thanks to these two little companions for sharing their life paths alongside humans, showing affection, love, and loyalty.**

## Part 2. Technical Document.

### 1. Development Goals.

• Create a stable 2D game with animation and simple controls.

• Provide a template for future NS projects.

### 2. Technologies Used.

• **Game Engine:** Construct 3.

### 3. Project Architecture.

• The project is divided into several blocks, each responsible for a specific part of the game:

• **PLAYER:** main character movement (holding the Space key).

• **JELLYFISH:** jellyfish spawning, movement, collision handling with the player (life loss), game over condition.

• **BACKGROUND:** background movement (music support is planned).

• **STARFISH:** star spawning, movement, score increase when collected.

• **HEARTS:** life count changes and animation of their removal.

• **GAME OVER:** game restart using the Space key, final screen with best score and current score.

### 4. Project Structure.

• The project consists of one main file: DiverGame.c3p (Construct 3 format).

• This file contains the entire game: assets, music, interface settings, sprites, and all logic.

• Construct 3 is required to run the project.

### 5. Key System Components.

• A set of game assets.

• Sprites.

• Global variables (score, lives).

• Event system (Event Sheet).

• Collision logic.

### 6. User Interface Implementation.

• The interface is built using pixel-style assets selected from compatible sets.

• UI elements are placed at the top of the screen (corner and center) for convenience.

• The visual style is consistent throughout.

### 7. Development Process.

• Creation of sprites for main characters, starfish, jellyfish, and background.

• Definition of basic mechanics for each sprite and their interactions.

• Addition of lives system, score, and game over screen.

• Uploading assets and adding music.

### 8. Main Challenges and Solutions.

• **(1)** Challenge: main characters go beyond the map boundaries.

Solution: barrier sprites (split) were added to limit the movement area.

• **(2)** Challenge: a jellyfish appears too close to a star, making it impossible to collect without losing a life.

Solution: spawn zones and object coordinates were adjusted to prevent such situations.

• **(3)** Challenge: lively sprite animation is required.

Solution: multiple images in different positions are sequentially switched to create a movement effect.

### 9. Current Project Limitations.

• No полноценного main menu.

• No music settings or ability to disable it.

• After the game ends, a results screen appears, but the game continues running in the background – pause logic needs improvement.
