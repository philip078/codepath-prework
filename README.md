# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Philip Truong

Time spent: **#** hours spent in total

Link to project: https://glitch.com/edit/#!/viridian-quiver-boursin?path=index.html%3A1%3A0

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

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!
- [x] I added a patternAmount, which changes the length of the pattern, very helpful for testing.

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![x] https://github.com/philip078/codepath-prework/blob/main/game_button_behavior.gif
![x] https://github.com/philip078/codepath-prework/blob/main/losing.gif
![x] https://github.com/philip078/codepath-prework/blob/main/start_stop_random.gif
![x] https://github.com/philip078/codepath-prework/blob/main/winning.gif
https://www.youtube.com/watch?v=XruzoeS4KRY (A video explaining the game [has the audio clues])

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
Searched up “css colors” just to make my webpage look different/unique
https://www.w3schools.com/cssref/css_colors.asp

Searched up “how to give something a class html” because i wasn’t sure if it was supposed to look like this: <button id=”button1”, class=”hidden”> or without the comma, turns out it’s without the comma.
https://www.w3schools.com/tags/att_class.asp#:~:text=The%20class%20attribute%20specifies%20one,elements%20with%20a%20specified%20class.

Searched up “javascript audiocontext methods” to see and read about the methods audioContext has, to help understand the code I was pasting in. It only helped my understanding slightly.
https://developer.mozilla.org/en-US/docs/Web/API/AudioContext

Searched up “javascript Math.random” to read about it’s documentation, helped me get the right number range.
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random

Searched up “javascript printing values” to help me test out the new code I added, didn’t know if “console.log()” would help me do what I want.
https://www.w3schools.com/js/js_output.asp

Searched up “javascript adding to array” to find out how to add elements to the pattern list, as “pattern.add()” is not the method, turns out it is “pattern.push()”.
https://www.w3schools.com/jsref/jsref_push.asp


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
One of the major challenges in creating this submission was at the final section where I had to add the game logic.
The flow chart was very useful in guiding my if statements and laying out the skeleton of the logic.
However even though I knew what I should do like “if the guessed button isn’t the same as the correct” for the if statement’s condition, but I didn’t actually know how to implement it.
I feel like this problem arose from me just following the instructions and not fully understanding it, even though I did take the time to read and understand it somewhat.
I think it’s different when I’m actually the one who “thought” that line of code up, so when I need to recall it, it’s there as the one who made it, I fully understand it.

In order to fix this problem I went back through the project and looked at all the variables and everything.
Like noticing the pattern variable and realizing I could check the guessed button, with its associated button in the pattern.
As well as peeking at the solution and making sure I understood why that code was written like that.
I definitely feel like that helped, to where I feel like I can make a project similar to this in the future.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
After this project I do have multiple questions about web development.
One of them being are there any other languages that can be used in web development, like Java or Python? Are those languages used in web development? Why or why not?

I am also curious about how the more complex things on websites are made now, like on youtube, when you hover over a video, how did they make it so a preview of that video is played?

I also wonder how those website making companies are doing things behind the scenes, as just making this one little game, was already complicated, how is making a whole custom website template done?


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I don’t know where else to include this, so I’ll do it here, it took me around 2 hours to finish the prework project.

If I had a few more hours to put into this project I definitely think some of the optional features seem pretty cool.
Especially the clock timer, that times out the player if they take too long at a guess.

One thing that I definitely wanted to do if I had more time, was putting in more buttons, more specifically 9 of them.
This is because, this game reminds me of the used-to-be popular game “Among Us”, where one of the little mini games in it was similar to this.
Then I could’ve themed the whole website to be Among Us themed, which would have been pretty cool.
Like the buttons could be in the character shapes and things like that.




## Interview Recording URL Link

[My 5-minute Interview Recording] https://youtu.be/LzZL2LC_lZo


## License

    Copyright Philip Truong

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.