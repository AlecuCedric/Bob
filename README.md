# HappyBoB-Godot-Game
2D Platformer

Game made in Godot Engine
features:
Scenes:
  Player - scrit + sprite + colision
  Rock - script + sprite + colision
    called by player when using the throw function
  Ammo - script + sprite + colision
    interact with UI and player ammo
  Title Screen:
    start gane / quit options
  Cinematic:
    cinematic at the start of the game
    Text box with exposition
  Tileset
    tiles with colision and sprites for the levels
  Levels:
    Level 1:
      Short tutorial explaining controls
    Level 2
    Level 3
      Cave level
    Level 4
      Final level
    Level 5
      Boss arena
  UI
    Ammobar
    Health
  Enemy ai:
    BananaMonster_Blue_Enemy - script + sprite + colision
      Walk until colision with wall
      Hit player if he is in range
      Die if player jumps on head 
             player hits
             player throws rock
    OwletMonster_White_Enemy - script + sprite + colision
      Walk until colision with wall
      Hit player if he is in range
      Throw rock at player if he is in sight
      Die if player jumps on head 
             player hits
             player throws rock
    Boss - not finished
      Follow player
      Attack player
      Has to be stunned with a rock and than the player has to jump on its head 3 times to defeat it
  NPC:
    PinkMonster_Pink_NPC - script + sprite + colision
      static / basic walk /
    PinkMonster_Pink__End_level_NPC - script + sprite + colision
      static
      interact with colision box to get to the next level
resources: https://www.youtube.com/watch?v=MMsMtPVUtUE&list=PLyckz_-Rzq6ClGevL2fneJ5YJnMPKWa4M
