# Game Design Document

## 1. Game Overview
### 1.1. Game Concept / Genre
Our game is a platforming game with a fantasy medieval theme. It will revolve around solving how to complete each level, as we plan to have different objectives for level completion. These alternative objectives will also be avialable as alternate completions for playermade levels
### 1.2. Game Flow Summary – At a high level, how does the game progress?
### 1.3. Look and Feel – What is the basic look and feel of the game? What is the visual style?
We aim to have a fantasy medeival theme; a fantasy theme with magic taking place in a castle/medieval setting. The feel of the game will be more or less a platformer with some critical thinking elements on which doors to open/ which route to take.
## 2. Gameplay and Mechanics
### 2.1 gameplay
####  2.1.1-the player is greeted by the introduction screen which includes a “login” button , a “play” button to start pre-made levels in the game , a “build” button to access the level editor , and an “options” button for configuration
####  2.1.2- the player will move left , right , up or down to reach and complete objectives that in turn help progress the main mission
#### 2.1.3- each level will have a mission that includes 1 or more objectives , the level is completed after required objectives are finished.
#### 2.1.4- puzzles can include “ placing blocks  on pressure points to unlock a door” , “ timed jumps to reach certain areas” or “ defeat enemies in a set amount of time”
#### 2.1.5- objectives will depend on the level , they can be “ collect all coins” , “ reach a certain area” , “ complete a puzzle” or “ defeat boss” .
#### 2.1.6- the player progresses through the game by completing the set objectives of the level , the challenge aspect will depend on how the level is made  , it is possible for the player to level up within the level and access more abilities to help complete the level , levels are considered  a full game experience so they are intended to be long so the player can get a sense of progress , and for the levelling system to not be trivial. 
#### 2.1.7- checkpoints will be used  to save progress , unlike quicksave  , checkpoints help us avoid errors that can happen if a player saves at a point in the game where saving is not expected , it also helps the player by not having them return to the game in an inconvenient position and checkpoints also work as an auto-saving system that makes sure the player doesn’t need to remember to save every few minutes.
### 2.2 mechanics
#### 2.2.1- most objects in the game will be ”pulled down by gravity” unless they have a float or fly attribute  , jumps for instance work as a temporary fly  before being pulled down , the player can’t move through walls , except with certain abilities or through transparent walls , the player and NPCs will be able to move through each other.
#### 2.2.2- movement in the game includes moving left or right , jumping or flying up  , and falling down , the player will either be in a running state or a walking state  which determine the speed of movement , movement  in water is slowed down and  movement animation is changed.
#### 2.2.3- there will be multiple interactable object in the game  , interaction will be mostly initiated through hitting the X key , objects can be doors , portals, NPCs with dialogue .
####    Helpful items like power-ups , will have to be picked up by interacting with them and they’ll be stored        in the inventory until used by the user.
#### 2.2.4- actions performed by the player includes movement , interaction and combat , there are also other buttons that will open up the menu , inventory or ability customization.
#### 2.2.5- combat is done through  activating some of the player’s abilities , with the starting ability being a no-cooldown short-range hit  , with the player unlocking more as they progress , enemies  are  harmful themselves (touching them lowers health) they can also fire hostile projectiles  ,  the damage differs depending on the hostile object , reaching 0 health ends the level.
#### 2.2.6- the player collects coins or items throughout the level either by finding them and picking them up or by dropping them from enemies  , they can then sell or buy items in a hub that is usually at the start of the level but can be in different areas, currency drops become less frequent as the player’s wealth increases .
#### 2.2.7- the screen will follow the player throughout the level , the entire level will be one screen with the view focusing on the player and cropping out the rest of the level , transitions will be used when the player activates a portal or a teleport “ability” that requires instance relocation of the view of the screen.

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
### 6.1. Common Enemy AI
   Enemies move from left to right. When they hit an edge, or move to far, they reverse direction.
### 6.2. Boss Enemy AI
   Bosses target the player. They move in the direction of the player, and when the player is within attack range, the boss attacks.
## 7. Game Art
- Style: Pixel Art
- Source: https://finalbossblues.itch.io/pixel-platformer-pack
- Key Assets:
  - Player
  - Stone Block
  - Totem Enemy
  - Skeleton Enemy
## 8. Level Editor
### 8.1. Overview of level editor
   The editor includes all tiles, enemies, and items from the core game. A user can use this editor to create their own levels. These levels can then be saved and loaded for later play.
### 8.2. Interface
   Insert Link To Drawing
### 8.3. Menu System – What will the menu system look like?
   Insert Link To Drawing
### 8.4. Transition 
   During the creation of a level, the user can click the play button at anytime to start and test the level after setting the initial player spawn point.
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
