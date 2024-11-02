# Game Development Senior Project - University of Florida

Welcome to the repository for the game project, _Nightfall_, developed by Ethan Fiore in Spring 2024 for CIS4914 (Senior Project) at the University of Florida.

## About the Game
This project is a 2D top-down action RPG where the player embarks on a heroic journey through lands plagued by enemy skeletons. Will you be able to vanquish the monsters and save the world?

## Getting Started
To play the game on Windows, simply download the repository and unzip. Then, run the executable file provided. No additional installations or configurations are required.
Mac and Linux release coming soon!

Note: Due to copyrighted assets in the game, the source files of the project cannot be uploaded.

## Features
- **Engage** in strategic battles against four unique classes of skeletons.
- **Explore** a vast 3-level world spanning beautiful grasslands, murky swamps, and scorching deserts.
- **Utilize** various weapon classes and magic abilities to overcome your foes and protect your home.
- **Discover** health and weapon pickups scattered throughout the world to aid you in your journey.
- **Jump** to your favorite level with the level select functionality.
- **_Find_** the hidden easter eggs on every level.

## Development Details
After developing the Nightfall demo in Spring 2022 (play at https://github.com/ethanfire/NightfallDemo), I really wanted to make it into a full game. This game greatly expands on the combat, enemy AI, and scope of the first game, boasting 3 different weapon classes (each with multiple tiers), 2 magic attacks, 4 unique enemy types (with regional variants), and 3 bosses to finish off the 3 regions to explore.

As with the first game, revisiting and developing a full Nightfall game came with many lessons. I wanted to develop new and smart enemy AI, which I did by using a state machine and giving them different abilities, similar to what the player has. I also wanted to make very large maps for the player to explore and fight these new enemies, and I certainly pushed the engine to its limits of what tilesets could be (without getting into chunk loading strategies). Switching from Unity to Godot for this game helped me develop more as a software engineering, along with having to utlize community help for learning a new language GDScript. Using version control this time around certainly helped save me as well ;)

## Credit
Huge thank you and shout out to:

- [finalbossblues](https://finalbossblues.com/) for developing the amazing character, enemies, and weapon sprites

- [CraftPix.net](https://craftpix.net/) for developing the outstanding tilesets

- Custer Gilchrest for working on all of the immersive audio programming and sound design, and helping make our final presentation and semester at UF a blast :)

## Teaser Images
**Bring the heat to your enemies!**<br/>
<img width="553" alt="Fireball" src="https://github.com/user-attachments/assets/7175c724-43bd-4303-b18d-4d40203dc52d"><br/>

**Knock 'em dead with ground pound!**<br/>
<img width="548" alt="Groundpound" src="https://github.com/user-attachments/assets/73b6602d-3a4b-4b8e-a94c-8759c9377079"><br/>

**When all else fails, slash away!**<br/>
<img width="544" alt="Slash" src="https://github.com/user-attachments/assets/2a569d2c-9033-420a-88af-ba9435f1781a"><br/>

**Beware the Skeleton King!**<br/>
<img width="595" alt="FinalBoss" src="https://github.com/user-attachments/assets/c8b0d814-1cfb-4dfa-93a1-09e29f6c4cab"><br/>

**Explore vast new lands!**
<img width="1231" alt="Grasslands" src="https://github.com/user-attachments/assets/a8f1a61b-09ae-41b9-9899-5e1d240ab3be">
<img width="1227" alt="Swamp" src="https://github.com/user-attachments/assets/4d27beed-49f0-4c91-aee4-c587eb318e58">
<img width="1229" alt="Desert" src="https://github.com/user-attachments/assets/a7e0eb05-0709-491b-8b44-fcefdf137f7d">
