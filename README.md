# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **KHANG TA**

Time spent: **4** hours spent in total

Link to project: https://accessible-serious-manx.glitch.me/

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

![](https://media0.giphy.com/media/v65JIDattM2AOyToy3/giphy.gif?cid=790b7611e930544adfa8fc405d1706dd0f46cc371603fc79&rid=giphy.gif&ct=g)
![](https://media1.giphy.com/media/tv1Wmh8Cq8xxWVY2t9/giphy.gif?cid=790b7611b24f92c7a481343511a95f48956956582e861efe&rid=giphy.gif&ct=g)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

I used https://www.w3schools.com/ to help me with understand the basic HTML/CSS and JavaScript.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

I am very new to web development. It took me quite a bit of times to grasp the structure and syntaxes of HTML/CSS and JavaScript. 
Most of the CS classes I took in my school used mostly C++, which is static-typed language, and they focused mostly on command line interface. 
JavaScript is totally different. It is dynamic-typed and interacts with HTML/CSS to construct a GUI of a website. 
Because of being new to such interaction between JavaScript and HTML/CSS, most of the challenges I encountered were from programming the mechanism of the buttons. 
For instance, I followed through instruction on the pre-work site until I reached the “Start and Stop Functions”. 
I typed the codes according to the instructions, but I kept getting error when I clicked the ‘Start Button’. 
I formed a hypothesis that the bug was around the ‘document.getElementyById()’. I referred to the provided material from the website and W3School to understand what this function do. 
I figured out that error came from the mistype ‘classlist’ instead of ‘classList’ with the capital ‘L’.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

I have so many questions about web development. I know this submission just barely scratch the surface of web development. 
There are so many parts of web development that I want to know: how a website works as a whole (front-end and back-end)? 
For front-end, how do some websites can have complex animations such apple.com? How does a web application like Spotify work? 
Is it different than the Memory Game I have just made? How can I create one? For back-end, how does a website run on a server? 
What connects front-end with back-end? How do I host a website? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

If I had a few more hours to work on this project, I would spend on doing a few things. 
First, I would do all the optional features. Second, I would try to find a way to make the pattern randomized because with a fixed pattern, the player would remember it after a few rounds, and therefore, it ruins the game. Lastly, I would spend more times on the appearance of the game. The button’s design and the monotonic background look somewhat boring and not eye-catching. I would make the title flashing and animated, choose a nice background, and I would also add a pleasant music theme.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://fullerton.zoom.us/rec/play/MTc4c-9rqrmHnTT5eNeZLnpYEJMe7-Tb_r9zXo8WvQ1QCgMV7iqAfdOoBzE4Wwufzk7k18h3FVqMHTUu.yjucKJFBqe8N4yRr?startTime=1650347258000)


## License

    Copyright Khang Ta

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
