# Game Design Document

## 1. Game Overview
### 1.1. Game Concept / Genre
Our game is a platforming game with a fantasy medieval theme. It will revolve around solving how to complete each level, as we plan to have different objectives for level completion. These alternative objectives will also be avialable as alternate completions for playermade levels
### 1.2. Game Flow Summary – At a high level, how does the game progress?
### 1.3. Look and Feel – What is the basic look and feel of the game? What is the visual style?
We aim to have a fantasy medeival theme; a fantasy theme with magic taking place in a castle/medieval setting. The feel of the game will be more or less a platformer with some critical thinking elements on which doors to open/ which route to take.
## 2. Gameplay and Mechanics
### 2.1. Gameplay
#### 2.1.1. Game Start / Login (How does the user start playing the game)
#### 2.1.2. Game Progression
#### 2.1.3. Mission/challenge Structure
#### 2.1.4. Puzzle Structure
#### 2.1.5. Objectives – What are the objectives of the game?
#### 2.1.6. Play Flow – How does the game flow for the game player
#### 2.1.7. Save Progress – Save Points? Quick Save? Checkpoints? Explain why
### 2.2. Mechanics – What are the rules to the game? This is the model of the universe that the game works under.
Think of it as a simulation of a world, how do all the pieces interact?
#### 2.2.1. Physics – How does the physical universe work? (ex: gravity, collisions)
#### 2.2.2. Movement in the game (limits/types of movement, controls)
#### 2.2.3. Objects – How to pick them up and move them (ex: walk over, press button, etc.)
#### 2.2.4. Actions – Switches / buttons / object interaction
#### 2.2.5. Combat – How does the player do combat with enemies?
#### 2.2.6. Economy – What is the economy of the game? How does it work?
#### 2.2.7. Screen Flow -- A graphical description of how each screen is related to every other and a description of the
purpose of each screen. (example: mega man, sometimes screen flows smoothly to the right, sometimes it
transitions a full screen at a time)
### 2.3. Game Options – What are the options and how do they affect game play and mechanics?
### 2.4. Cheats and Easter Eggs – (Including cheat codes? What are the input method and their effects?)
## 3. Story, Setting and Character
### 3.1. Story and Narrative – Our game is not heavily story driven, but include some sort of back story / motivation for
why the player should care to complete the game.
### 3.2. Game World
#### 3.2.1.General look and feel of world (overworld vs. individual levels)
#### 3.2.2.Areas, including the general description and physical characteristics as well as how it relates to the rest of
the world (what levels use it, how it connects to other areas)
### 3.3. Characters. The game should have a few characters (including the main player character, bosses, small story)
## 4. Levels
### 4.1. Overall structure of levels. How are they accessed, how are they completed?
### 4.2. Level Design - Description of level design. This document does not need to include a description of all levels that
will be in the game (we are making a maker after all), however, describe characteristics of a level so that a
reader can get an idea of how one looks / plays.
## 5. Interface
### 5.1. Visual System. If you have a HUD, what is on it? What menus are you displaying? What is the camera model?
### 5.2. Control System – How does the game player control the game? What are the specific commands?
### 5.3. Audio, music, sound effects – When is music playing? When do sound effects play?
## 6. Artificial Intelligence
### 6.1. Enemy AI – Describe some behaviors that enemy objects and characters will have. (ex: move toward player,
shoot at player, run away, etc.)
## 7. Game Art
### 7.1. Key assets, how they are being developed. Intended style.
## 8. Level Editor
### 8.1. Overview of level editor (scope, purpose)
### 8.2. Interface – How will the user interact with the editor?
### 8.3. Menu System – What will the menu system look like?
### 8.4. Transition – How will you test the levels made in the editor?
## 9. Player Account
### 9.1. Player Login / Profile – Stores / displays save games, levels, scores, achievements, etc.
Players will be able to login via username and password. Username's will be unique. Once logged in, the player will be able to play from where he left off on the main campaign, or play/create user levels.
A player's profile will include his own levels, his favorited levels, and the amount of unique levels said player has beaten. The number of unique levels comlpeted will be stored on a grand leaderboard. Player's can find other player's profiles by a search, or finding their player id on a leaderboard.
Levels will have a leaderboard of 10 players, a level rating, the player id of the creator, and the level data.
### 9.2. Save Game – Quick Save vs. Save Points vs. Checkpoints
We aim to have the progress of the main campaign saved on a perlevel basis. We also aim to have checkpoints in these levels, in which players will return to if they die, aswell as reverting the level back to a previous state in which the checkpoint was passed. We aim to be able to save the progress of one level to the database, though starting a level different from the saved level will result in loss of progress.
### 9.3. High Scores – Saving high scores / fastest times?
Players will have their "number of user created levels completed" tracked. From the leader board, people can veiw the player profile's of these players, which will include what was mentioned above.
Another feature that we are looking to implement is the ability to lookup someone's level and to find the fastest completion times. These will show the time the player completed the level along with the player id of the player, sort of like a mini leaderboard for the level. From here, the player can look at the player profile of these players, or look at the profile of the creator.
### 9.4. Achievements – What type of achievements to store?
We aim to store the player's main game progress, aswell as a player's count of main level completed. Since levels will have their own leaderboards aswell, players can compete for the fastest time on any user created level. There will also be the grand leaderboard that player's can compete for.
We also aim to have steam like acheivements, that will also be stored to a player's account. These will be more or less related to the main campaign, but some will be obtainable through/exclusive to player made levels.
