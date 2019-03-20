## Introducing Melody Hero

Do you like the idea of Guitar Hero, but never could get into to the music? Melody Hero let's you play your favortie song in a mobile desktop game! Play your favorite songs on the go with Melody Hero!

### Contact
Nida Pervez:Nidapervez2020@u.northwestern.edu
Alex van der Heijden: vdhalex@u.northwestern.edu
David Wolff: davidwolff2020@u.northwestern.edu 

Machine Perception of Audio and Music Northwestern University Professor Bryan Pardo

### Motivation
  Melody Hero was inspired by a game that all three of us enjoy playing: Guitar Hero. The ability to interact with a game while playing songs was appealing to all of us, but we all agreed that the music choice for Guitar Hero was not for everyone. Another downfall to Guitar Hero was that you could only play it on a console, meaning that it lacked mobility. To combat those two restrictive measures of Guitar Hero, we came up with the idea Melody Hero. Melody Hero allows users to play a game similar to Guitar Hero, but with any song of their choice and anywhere! 

### Overview
  Similar to Guitar Hero, Melody Hero requires the user to select a song to play. Afterwards the page will generate a game interface with pieces moving from the top of the screen to where the “Keys” are on the screen. This is also similar to Guitar Hero where the notes are coming closer to where the symbolic-images of the keys are. Once the note is on top of the key-image, the user must press the button that corresponds with that key-image. In our case those are the keyboard button D, F, J, and K. When the user presses the keyboard button at the correct time, their score will increase, ultimately giving them a percentage score, also similar to Guitar Hero.
  
### Validation
  Melody Hero was built using Python, JavaScript, and Melodia as a pitch tracker. Melody Hero first requires the user to input their song as a .wav file. The file then goes through Melodia’s pitch-tracking algorithm where we can get the frequencies of the notes. The frequencies then go through another algorithm to dictate what keyboard-button they will correspond to. We calculate the onsets and send both the onsets and frequencies to the front end so that they can be processed and shown on the screen. The player then has to press the respective letter on the keyboard when the block is over the piano-key-looking part of the interface. The player plays through the entirety of their song and accumulates points for every note pressed at the correct time. HOW DO WE MEASURE SUCCESS????

### Results
....

![](https://github.com/pervezn/MelodyHero.github.io/pic0.png)
![pic1][pic1]
![pic2][pic2]
![pic3][pic3]

