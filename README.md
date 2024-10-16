# Individual-HW1-Sample-Template
Individual-HW1 Sample/Template

FR | Description | Priority
--- ------------- ---------
FR1 | Game must allow player to sign in to be able to save their progress | 3
--- _--------------------------------------------------------------------  ---
FR2 |  game must allow left, right, up, down, with WASD keys | 4
---  -------------------------------------------------------- ---


Part a
FR1 - Game must allow player to sign in to be able to save their progress - 3
FR2 - game must allow left, right, up, down, with WASD keys - 4
NFR1 - game may have about 2-3 enemies
FR1 - user should be able to kill enemies - 5
NFR2 - game may have about 2-5 weapons
FR2 - user should pick up weapons - 4

Part b
Usecase 1 - player moves using keys
TUCBW - Use the WASD keys to move towards an enemy
TUCEW - Use weapons to kill enemy
Usecase 2 - player signs into game
TUCBW - Player starts/continues game
TUCEW - Player can view their current score

actor | game
------------
      |Player signs into game
      If the player signs in, they have the option to look at their score or start/continue a game

      2a. If they choose to start a new game, then they begin at the first level with no inventory/weapons/powerups

      2b. If they continue the old game, they keep the score, their inventory, and they start at the level they previously stopped at

      2c. If the user defeats the enemies within the allotted time they can move onto the next level, otherwise they have to start the level over

      2d. If the user makes it to the final level and defeats the warden, they win the game, otherwise they have to start the level over again

 











![DomainModel](https://github.com/user-attachments/assets/a9d74868-8539-4f45-84b8-0406b21f9780)
![UsecaseDiagram](https://github.com/user-attachments/assets/40016502-7a0d-49db-a214-1123ec6fa8f6)
