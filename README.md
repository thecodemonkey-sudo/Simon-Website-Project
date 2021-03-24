# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Kevin Tian**

Time spent: **2** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

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
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
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
![]https://recordit.co/eBAsJ5xN6F


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
The only website I used to help me complete my submission was
https://courses.codepath.org/snippets/summer_internship_for_tech_excellence/prework?utm_campaign=CodePath%20SITE%202021&utm_medium=email&_hsmi=112744221&_hsenc=p2ANqtz-91DDq1Gx2ZcTyVde1sKlqf87v0uhQMZqxXmSqdPegBJE8oCgykAnrPnBF-VLTUphl2GttHtXsCTXk63huLsJv3fhdjjw&utm_content=112744221&utm_source=hs_automation#heading-3-background

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
When I was creating this submission, I ran into a small problem with the .lit and the lightButton() function.
I looked at the console and it said that the classList couldn't be found in the lightButton() function so
I just went through the .css file to see if my buttonX.lit was working fine, and it turned out that
I had mistyped something, so I just fixed it and everything worked.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
After doing this activity about web development, I want to learn more about it. Some questions I have are
what a web developer's research process is like and how they design the webpage. Do they have a picture in mind
that they are trying to recreate through code? Or is it all just done while they are coding?
Also, how do you implement custom design for people? For example, websites like Shopify let the user
customize their own website. How could a developer implement that without changing the css or html?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on this project, I would spend them adding in more features.
I would want the game to go on infinitely until a wrong button is pressed instead of being limited by a few button presses.
The game would ideally also be random presses everytime, so that people could replay without
just memorizing the first few buttons. I would also add in a challenge mode where things would
get way harder. For example, there could be a sound only mode that hides all the buttons while
the sound is playing and you have to guess which button it is. I would also add in a flashlight mode
where everything is dark except for a small circle around the cursor.


## License

    Copyright [Kevin Tian]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.