# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Soren Campbell**

Time spent: **#3** hours spent in total

Link to project: (https://spark-dot-clavicle.glitch.me/)

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/q64xb1n.gif)

![](https://i.imgur.com/EVRaEUK.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

    I did not use any outside resources besides basic online documentation.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
    The main challenge I encountered in creating this submission was reorienting myself to javascript, HTML, and CSS. Given that we do not do a lot of frontend work in my classes at school, I often have to remind myself how to use these tools. I overcame this challenge in the way that I overcome all challenges when I program -- read documentation online. Being able to research effectively when you get stuck is such an important aspect of programming and this project tasked me with doing just that. Aditonally, I really wanted to work on the optional features but I found out about this pre-internship program the day the application was due so I did not have time to do so. However, looking over the optional features I am sure that they would have been a fun challenge. In particular I think that adding multiple strikes/lives for the player would be enjoyable. To do this I imagine that we would need a variable to track strikes, then when the player makes a mistake we update the strike counter and when the counter reaches the set number of strikes we would call loseGame().

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

    Besides HTML, CSS, and JavaScript, what other tools/languages does a web developer need to know? What are the first things that are recommended to learn as a web developer? Why is web development and frontend work not taught as much in college?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

    If I had more time to work on this project I would take a stab at some of the optional features. In particular I would look to add a randomized secret pattern so that when a player begins a new game it will not be the same pattern as before. This would prevent the player from just memorizing the pattern once and then always winning, I also think that styling the game more could be fun. One possible feature for styling that I might implement is changing the color and sound of the buttons everytime the player starts a new game.This would make the game look more exciting but also add to difficulty as the player has to reorient themselves to the look and feel of the game each time they start a new game. One last thing I would like to do with this project is make it display better on mobile devices. As of now most of the functionality works on mobile but I would like it if all the buttons fit on the screen without the need to scroll.



## Interview Recording URL Link

https://drive.google.com/file/d/1PMY9wg1h1gtfVLuti2kth1OX9DnQRKrf/view?usp=sharing



## License

    Copyright [Soren Campbell]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.