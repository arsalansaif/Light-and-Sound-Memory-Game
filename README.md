# Pre-work - *Sound and Light Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Arsalan Saif**

Time spent: **3** hours spent in total

Link to project: (https://glitch.com/edit/#!/obsidian-gem-sodalite?path=script.js%3A15%3A8)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
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
![](https://i.imgur.com/6OsQcSa.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[I did not use any outside resources as the tutorial itself was very helpful in understanding the basics of this assignment.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[A challenge that I encountered while creating this submission was of the gif. Once I screen recorded my assignment, I converted it into a gif but the sound didn’t play in the gif. I was confused on how to include the sound of the game but soon realized that gifs don’t include sounds so I just submitted the gif in the appropriate area of the README file. Another difficulty I faced while creating this submission was when I had to push it to github, since I have not used glitch before, I was stuck on how I would upload my code to github. Fortunately, the instructions were very clear and displayed a proper way to upload it on github. Also 
]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[After completing my submission, I have several questions about web development. Firstly, can we use API in web development and how do we implement it? Secondly, What are some ways to optimize the game's loading time? What is the difference between global constants and global variables in JavaScript? What is the main difference between the functionality of CSS and JavaScript? What tools can we use to find a performance bug? How can you add a timer on the screen which counts the time spent on the website and stops when the user has left? Also, how does one organize its JavaScript code? Lastly, what are some functions that can be used in HTML to import data from another domain?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had a few more hours to work on this project, I would have spent my time doing the optional features to configure the game. Specifically, I would work on adding a ticking clock because it uses methods such as setInterval and clearInterval which required some background knowledge. Upon testing the game I realized that the game speed was slow, so if I had the chance, then I would speed up the clue playback on each turn to make the game harder as it goes on. I would change the clueHoldTime constant to a variable and update it as part of the playClueSequence so that it decreases on each turn. This part is crucial for the game as it makes the game more challenging and requires quick response.]


## License

    Copyright [Arsalan Saif]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
