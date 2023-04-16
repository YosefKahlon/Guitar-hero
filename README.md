# Guitar-Hero
 
https://kinwon.itch.io/guiatr-hero


In this project, I created a Guitar Hero-style game. The player must press a button that matches a falling cube's color in time and in the correct position to score points.

## Gameplay
The game features four spawner cubes of different colors that fall randomly from the top of the screen, and four static cubes of the same colors at the bottom of the screen. The player must press the button that matches the color of the falling cube.. The player scores points for hitting the correct button.

## Game system 
I used Unity's InputSystem to detect button presses, and I used tags to differentiate the falling cubes' colors. I created a GameSystem script that handles the game's mechanics, including adding points to the player's score and changing the color of the static cubes when the player hits the correct button.

 used the Box Collider 2D and Rigidbody 2D components to detect collisions between the falling cubes and the static cubes. When a collision occurs, the CanPress boolean is set to true, allowing the player to score points by pressing the correct button.

I also used the NumberField component to display the player's score on the screen. The SetScoreField function in the GameSystem script assigns the player's score to the NumberField component, allowing the score to be updated dynamically during gameplay.


* OnTriggerEnter2D(Collider2D other)
* OnTriggerExit2D(Collider2D other)


* Update()
* NumberField.cs

## controller 

* Up arrow\W - red cube.
* Down arrow\S - blue cube.
* Rigth arrow\D - yellow cube.
* Left arrow\A - green cube.


## Editor version 
2021.3.18f1







