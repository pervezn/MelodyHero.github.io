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
  
![](pic0.png)
  
### Validation
  Melody Hero was built using Python, JavaScript, and Melodia as a pitch tracker. Melody Hero first requires the user to input their song as a .wav file. The file then goes through Melodia’s pitch-tracking algorithm where we can get the frequencies of the notes. The frequencies then go through another algorithm to dictate what keyboard-button they will correspond to. We calculate the onsets and send both the onsets and frequencies to the front end so that they can be processed and shown on the screen. The player then has to press the respective letter on the keyboard when the block is over the piano-key-looking part of the interface. The player plays through the entirety of their song and accumulates points for every note pressed at the correct time. We will measure our accuracy by comparing it to the pitch tracker as well as using user-performance ratings.

![](user1.jpg)
![](user2.jpg)

### Results
  While working on our project, we quickly found that the project we had in mind would have to be scaled down for our specific time frame. For those reasons, we mainly focused on being able to play any of the songs in the Medley database. However, the algorithms still work on any song, but to get the best outcome, we recommend using monophonic .wav files. In terms of checking its performance, we mainly focused on user-testing to see if the game felt like an actual game. After testing multiple users, we took into account their feedback and implemented the respective changes. Overall, from our user feedback, we know that it feels like a game, and that there are enough prominent notes to piece together the song. In terms of Justin Salamon’s pitch tracking algorithm, we acknowledge that the pitch tracker is not completely accurate and has flaws in it of itself, so we also found flaws in our pitches. We got our onsets using librosa, but we also found that our onsets were also sometimes flawed. Pitch tracking is already very difficult to perfect and despite Melodia being one of the best pitch trackers in the market, it is still not perfect.
![](includes.png)
This is the pitch tracker including all negative frequencies
![](Omitting.png)
This is the pitch tracker omitting all negative frequencies



###Gallery
![](pic1.png)
![](pic2.png)
![](pic3.png)

