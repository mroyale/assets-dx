# Mario Royale Deluxe Patch Notes
## Version 4.2.1
### 2023-05-07 - Hotfixes
* Fixed the emote menu being toggled while typing in chat
* Fixed rare instances where using an emote would cause the game to behave weirdly
* Fixed the "private lobby world select" button in the settings appearing where it shouldn't

## Version 4.2.0
### 2023-05-06 - Major Update
* Added Chat
>   Like private lobbies, you need an account to use the in-game chat.
* Private lobby world select looks better
>   Also added the ability to close the private lobby menu.
>   And the room code of the lobby will be shown when you join it

## Version 4.1.1
### 2023-05-01 - Technical Updates
* Fixed security issues on the server-side
* Added some missing Spanish translations
* Fixed a couple of Portuguese mistakes

## Version 4.1.0
### 2023-04-30 - Major Update
* Added Emotes
>   Press Left-Shift to toggle the emote menu and numbers 1-8 to pick an emote
* Added Private Lobbies
>   Click the "Private" button on the play menu and enter a room code to make a private lobby
>   If there's no room code, then you'll be put into a singleplayer private game
>   Please note that you need an account to play in private lobbies
* Pressing the return to menu/lobby buttons doesn't refresh the page anymore
* Collecting a life by getting 30 coins no longer resets the coin counter to 0
* Added the option to use a custom URL to load audio from in custom worlds
* Fixed a bug with the editor replace tool
* Fixed guest names not being uppercased like registered names

## Version 4.0.0
### 2023-04-16 - Major Update
* Added translations
>   Click the globe button in the top right to change the game language!
>   Major thanks to dimension for the Spanish translation, RayTheMaymay for the Brazilian Portuguese translation, and Pyriel for the French translation!
>   Also thanks to Captain for the globe button!
* Added new areas to the lobby
* The raccoon leaf uses a smoother attacking animation now
* Enemies have a better dying animation when you kill them with the leaf or a fireball
* The game now uses the font outline accurate to the original SMAS game
* Fixed being able to jump over the flagpole in World 2-1
* Fixed rare tile animation glitches in the menu background
* Reverted world file indentation due to inflated file sizes

## Version 3.3.0
### 2023-04-13 - New World
* Added a new Royale world: Tricorn Kingdom
>   This is a touched up Royale world of the Legacy version made by Pyriel

## Version 3.2.0
### 2023-04-13 - New World
* Added a new PVP world: Unfair Hockey
>   This is a new PVP world made by Pyriel

## Version 3.1.0
### 2023-03-17 - Menu Update
* If you’re reading this at the time of release, congratulations! Welcome to the new changelog view!
>   We’ll usually only show the most recent update here. The full patch notes have been moved to a Markdown document on GitHub which... oh, hi!
* SMASified the Discord button
* Added the editor button back, right next to the Discord button
* Added a 20 character limit to name input fields
>   This was already the case server-side, now we do it client-side as well
* Removed the S in Changelogs
>   Did you notice?
* Redesigned settings menu
>   Sliders are now shorter, white and have numbers next to them & a mushroom thumb. The symbol for active options has been changed from X to * (which shows up as ⭐ in-game).
* Fixed leaderboard button shadow
>   Thanks Captain!
* Removed stray white pixel from the Mario selection outline
>   Really important stuff, I know
* Fixed adjusted sound volume not saving
* Removed Herobrine

## Version 3.0.1
### 2023-03-17 - Bugfix
* Minor bugfixes

## Version 3.0.0
### 2023-03-16 - Major Update
* Added a new powerup: Hammer Suit
>   However, you cannot obtain it in any game world right now
* The server now runs at 60 frames per second instead of 30
>   This means that client updates are received faster meaning less lag
* Physics changes
>   You can now more easily leave the water by pressing the up button. Momentum is now canceled when going into pipes.
* Hammer Bros. properly use their hammer throwing sound now

## Version 2.11.1
### 2023-03-11 - Hotfix
* Added Lost Levels W1 to world select

## Version 2.11.0
### 2023-03-10 - Content Patch
* Happy MAR10 day! (if you’re in America)
* Added World 1 from The Lost Levels

## Version 2.10.0
### 2023-03-09 - Improvements
* Fixed Koopas falling very fast
* Bowser’s dying behavior is closer to the original SMB game now
* Added parameters to Piranha Plant: direction, static and no offset
* The game looks better on phones and smaller displays now
* Saving a world in the editor results in a much cleaner output that’s easier to read

## Version 2.9.0
### 2023-03-08 - Editor Patch
* The editor now tells you where platforms move
>   You can toggle this with the L key

## Version 2.8.1
### 2023-03-07 - Bugfix
* Fixed keyboard rebinding and testing not working while in-game

## Version 2.8.0
### 2023-03-06 - Content Patch
* Added new tile: Player Barrier
* Bugfixes and improvements

## Version 2.7.3
### 2023-03-05 - Editor Dark Mode
* The editor’s dark mode looks much better now. No more white input boxes or anything

## Version 2.7.2
### 2023-03-05 - Editor Patch
* When resizing a zone, objects, warps and spawnpoints no longer change their vertical position

## Version 2.7.1
### 2023-03-05 - Patches
* The test color for the controls menu is gold instead of green, so that you can see it better
* Fixed issues with metal spiny not working
* Fixed the brick block in 4-2 missing the star powerup
>   Thanks to Captain for this fix!

## Version 2.7.0
### 2023-03-04 - Content Patch
* The controls menu is now part of the main page
* You can also now change your controls while in-game!
* And the keyboard controls are now human-readable!!
>   Note that the key shown may be different due to keyboard layout differences.
* Added metal variant to spinies
>   These metal spinies behave like the ones in Mario Forever; they can’t be killed with fireballs. The only way to take them out is with the Star and Super Leaf.
* Reduced data usage with fetching leaderboard data

## Version 2.6.1
### 2023-03-03 - Hotfix
* Flag object is no longer required for flagpole sliding

## Version 2.6.0
### 2023-03-01 - Content and Technical Patches
* Happy Bosnian Independence Day!
>   Random but I want to celebrate my country’s holiday :)
* Added dev menu for developers
>   Just backporting things from Legacy. Moderation tools.
* Various small improvements and bugfixes

## Version 2.5.0
### 2023-02-26 - Game and Editor Improvements
* While ingame, you can go to the settings menu to return to the main menu or the lobby instantly
* Returning to the main menu now skips the disclaimer
>   You still have to wait at it for a second or two since the background needs to load
* Added tooltips to object parameters in the editor
* Warp pipes and tiles now use a dropdown menu so you won’t need to memorize warp IDs in the editor

## Version 2.4.0
### 2023-02-22 - Content Patch
* Added flip blocks
>   No worlds use this, again, for more variety for world builders
* Fixed death sprite being.. well.. weird

## Version 2.3.1
### 2023-02-22 - 99% Bugfixes
* Added a debug option to set your powerup
* Fixed funky sprite offsets while transforming from small to big forms
* Fixed a Super Leaf exploit allowing you to clip through tiles while crouch jumping
* Fixed being stuck in the idle animation if you were hit while crouch jumping
* Changed data type info in the editor to what it’s supposed to be

## Version 2.3.0
### 2023-02-21 - Content Patch
* Added crouch jumping
* Added a toggle in the settings to disable backgrounds
>   This is to improve performance on underpowered devices especially for worlds like Blackout Ring. However, this feature may not work completely since some worlds rely on backgrounds and such don’t use a reasonable background color.
* Small form now uses 16×32 instead of 16×16 sprites
>   To make modders’ lives easier
* The life icon uses the proper character head instead of their idle sprite
* Updated character select sprites so they don’t shrink
>   Not applied to Infringio since he was already fine. Thanks to Captain for helping with this!

## Version 2.2.2
### 2023-02-20 - Hotfix
* Fixed incorrect editor tool instructions

## Version 2.2.1
### 2023-02-20 - Hotfix
* Reverted leaderboard request interval adjustment

## Version 2.2.0
### 2023-02-20 - Content Patch
* New PvP world: Blackout Ring
>   This is an original map created by Sir Sins, Ray, Captain, Noemi, Syembol and Scyrulean. Enjoy!
* Slightly changed the disabled nickname icon

## Version 2.1.2
### 2023-02-19 - Hotfix
* Adjusted leaderboard request interval
>   This patch comes alongside server changes that fix database issues caused by the leaderboard. Due to the severity, we had to rollback to yesterday’s database, so some stats were lost. We apologize for the inconvenience.

## Version 2.1.1
### 2023-02-19 - Hotfix
* Slightly adjusted jump physics again

## Version 2.1.0
### 2023-02-19 - Content Patch
Leaderboards are back!
>   Press the leaderboards button on the main menu while logged in to see who are the best Mario Royale players!
* Improved control when crouching under a block
* You can now jump instead of just sliding, allowing you to move in both directions
* Enemies now use the proper stomping sound effect
* Slightly adjusted the physics
* Jumping physics are now slightly more like in SMB1, shorter jumps and all

## Version 2.0.0
### 2023-02-18 - The Wario Update
* Added Wario as the 4th character!
>   “How could you forget Wario’s tremendous wit? You can’t claim the Wit Star Stamp yet!”
* Added our beloved contributors to the credits area in the lobby

## Version 1.10.0
### 2023-02-18 - Content Patch
* Editor parameters are now separated into different input boxes instead of a single input box
* Added the Giant Gate, the Super Mario World goal pole
>   No worlds currently use this, this is just to future proof the Super Mario World... world
* You can set the number of tiles the goal post moves; this also corresponds to the post’s vertical hitbox
* Added 1-tile warp pipes
>   Still warp pipes, just ones that aren’t 2 tiles big
* Lobby music is now randomized
>   Instead of there being only one music track for the lobby, there’s now four! These include SMB3 worlds 1 and 4 map themes, Yoshi’s Island and the SMW special theme. We might even take suggestions from you guys in the Discord!
* Fixed different fireball positions depending on the direction you’re facing

## Version 1.9.0
### 2023-02-18 - Content Patch
* Made it so that you can’t change your nickname to be someone else’s name
* Added new tiles: Camera Lock/Unlock Y
>   Locks or unlocks the scrolling of the camera’s Y axis
* Fixed koopas not being able to break bricks
* Added a name filter so that you can’t have slurs in your name
>   Or generally any swear words in your name

## Version 1.8.0
### 2023-02-17 - Content Patch
* Fixed SMB2 (PvP) missing a block hit sprite
* Outline is now configurable in the text object
* Mario walks slower after sliding down a flagpole or touching an axe
>   This was done to prevent the level end jingle from cutting off in some worlds.
* Added toolbar to editor info screen, and also moved about button to it
* Added tiles: Warp pipe slow/fast and Conveyor left/right
* Revamped the patch notes and control remapping pages to look even better
>   This is a stopgap. We plan to move these pages to screens on the main menu in the future.

## Version 1.7.1
### 2023-02-16 - Hotfix
* Trimmed Mario Kart star music to loop better
* This ended up not doing as much as we would’ve liked. You probably won’t notice anything.
* Added disclaimer tooltip to the private button (for now)

## Version 1.7.0
### 2023-02-16 - Content Patch
* Added a new tile: Item Regen
>   When hit, the block regenerates after 5 seconds allowing it to be hit again. This tile has been added to all PvP maps.
* Fixed Fire Bros ignoring the player when it should only ignore enemies
* Fixed tile collision glitches
* Fixed item hierarchy; Fire Flower and Super Leaf are now treated as the same class
* Fixed a softlock that could be caused by infinite power transforming by removing hold times
* Bullet Bills explode after 10 seconds now since in some worlds they explode before even getting to the player

## Version 1.6.1
### 2023-02-15 - Stats Patch
* Fixed stats being added to your account if you’re in a private lobby

## Version 1.6.0
### 2023-02-15 - Content Patch
* New PvP world: Ice
>   This is a vertical stage based on the snow map from NSMB Mario Vs. Luigi. Have fun!
* Fire Bro fireballs no longer interact with other enemies
* HUD buttons are slightly larger now
* Reduced Piranha Plant vertical hitbox by 20%

## Version 1.5.0
### 2023-02-14 - Content Patch
* The HUD buttons in the top right corner are now SMAS styled
>   Thanks Pyriel!
* Your kills are now displayed in the top left corner below the coin counter
Bullet Bills now explode 5 seconds after being fired
* Removed Herobrine

## Version 1.4.0
### 2023-02-14 - Content Patch
* Added two buttons after reaching the podium: Return to Main and Return to Lobby
* The former will return you to the main menu, the latter will return you to the lobby.

## Version 1.3.0
### 2023-02-14 - Valentine’s Day Patch
* Happy Valentine’s Day! We’ve themed the lobby for the special day!
* Added a new tile: Random Warp
>   This warps you to a random point in the level. No worlds currently use it though.
* General bugfixes

## Version 1.2.0
### 2023-02-13 - Content Patch
* You can now use a slider to control the music and sound volume
* Infringio now uses a custom made fireball-throwing Glock-18 made in Germany

## Version 1.1.0
### 2023-02-12 - Content Patch
* In the Choose Game menu, hovering over a gamemode will display how many players are playing that gamemode
* Fixed axes displaying as flags in the menu background

## Version 1.0.1
### 2023-02-12 - Bugfix
* Fix Connection Interrupted screen when idling on the title screen for a few minutes

## Version 1.0.0
### 2023-02-11 - The Game
>   You just lost The Game.
* Welcome to Mario Royale Deluxe!
>   You can view pre-release commits [here](https://github.com/mroyale/MarioRoyaleDeluxe/commits/4708f064ac41be5b67fc550b85aa18d1bc012e8c).
