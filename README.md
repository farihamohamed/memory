# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Fariha Mohamed**

Time spent: **10** hours spent in total

Link to project: (https://quiet-excessive-stool.glitch.me/)

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

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
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

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](http://g.recordit.co/qOy1YxujXI.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[I used this website to find different shades of colors for the start and stop buttons: https://cssgradient.io/shades-of-green/.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[I had a some trouble creating the guess function on my own, even after I tried to peak at the solution I realized I didn't understand what was going on. I went back to all the variables and functions I had created and tried to understand what they did. Then I used the flowchart and along with the functions and variables I had already created to create a pseudocode version of the Game function. My code still had errors and was very inefficient, I was using too many else-if statements. I peeked into the code again and cleaned up the code using the solution and now it works.Another challenge I had was understanding the game, when playing it. It takes a while to understand how long to hold the button for. This can be very frustrating because when I was trying to record myself winning the game, I would lose and I wasn’t able to show that in the GIF. ]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[I have so many questions. One of them is, why isn't there an easier way to create the user interface so developers can focus on the logic? For example, when I was making the buttons, it was a very repetitive process that I would like to eliminate or simplify.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[I would try to add a feature that tells the user how long each button should be held for because it's a very confusing game. I would add numbers on top of the game buttons that specify how many seconds a button should be held for while the computer is playing. While the user is playing, I would change the button that is clicked to zero and show the number going up for every second the button is being held for. ]



## License

    Copyright [Fariha Mohamed]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.