# Whack-A-Mole

This project ties together the CSS features that I've learned so far inside of the App Academy Open Curriculum:
positioning, hover effects, transitions, and overflow. 

You can use these files to play a quick game of Whack-A-Mole that you can play and share with your
friends!

GET STARTED BY GOING TO: https://fuentesnina.github.io/Whack-A-Mole-HTML-Game/mole.html

![Final game movie]


## Developer Note

The original codes had a couple of bugs, which were modified in this version of the game. 
The orinal code only supported playing the game if no animation was enabled when the user clicked on one of the moles head.
It was prescribed to uncomment a section of the provided code in order to implement the feature. 
However, doing so broke the game: the moles would stop re-appearing they moles had been clicked on once. 
Therefore, instead of having 30 moles pop up and down until the end of the game, the moles would stop popping up after 8 appearances.
To fix this issue, it was needed to edit line 13 of the current code to remove the ommision of the "mole-whacked" moles so the code would continue
to run.
It was also needed to add a "remove" action inside of the popUpRandomMole function (line 22 of the current code) in order to disable the animation
triggered by clicking on the mole. Otherwise, the animation was constantly shown throughout the game... defeating its original purpose.

## Files List

That repository contains the following files:

* **mole-head.png** which contains the image of the mole's head.
* **mole-hill.png** which contains the image of the dirt pile.
* **mole.css** which is the file in which you will write your CSS.
* **mole.html** which is the file in which you will write your HTML.
* **mole.js** which is the file which contains the JavaScript that controls the game.





[Final game movie]:
https://appacademy-open-assets.s3-us-west-1.amazonaws.com/Module-Responsive-Design/interactivity/assets/moles-bonus-final.gif
