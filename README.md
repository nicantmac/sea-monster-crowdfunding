# WEB102 Prework - Sea Monster Crowdfunding
#### Submitted by: Nicholas Mack
#### Time Spent: 3 days spent in total

### App Overview
The Sea Monster Crowdfunding app is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded. Users can see stats about the total funds raised, the contributions, and top-funded games, and they can filter the games list to see funded, unfunded, or all games.


## Features of Website

Intro Section: The introduction explains the background of the company, including the total amount raised and the number of games that remain unfunded.

### Stats Section:<hr>

Total contributions: ```19,187 individual contributions.```<br>
Total raised: ```$800,268.```<br>
Top Funded Game: ```Zoo Tycoon: The Board Game```<br>
Runner Up: ```How to Read Minds 2 Kit: Ellusionist x Peter Turner1```<br>
Games Section: The "Our Games" section initially displays all games funded by Sea Monster Crowdfunding, with corresponding images and basic information about each game.<br>
Game Filters: The "Our Games" section includes three buttons: ```Show Funded Only:```, ```Show Unfunded Only:```, and ```Show All Games:```

Show Funded Only: Displays only games that have been fully funded.<br>
Show Unfunded Only: Displays only games that remain unfunded.<br>
Show All Games: Displays all the games, regardless of their funding status.<br>

Other optional features implemented were:
- ```Couple CSS changes (like two)```

### Video Walkthrough

Created with LiceCap and Imgur GIF: ![Walkthrough](https://imgur.com/a/hqUKGSb.gif)

### Additional Notes:
Challenges Encountered
Handling Dynamic Data: Initially, I struggled with dynamically populating the stats section and game list. However, I was able to use JavaScript to create the statistics and game data by storing it in a JavaScript object and accessing it using DOM manipulation methods like getElementById() and textContent.

Flexbox Layout: Aligning elements properly within the .stats-container section using Flexbox was challenging. Once I understood how display: flex and align-items: center worked, I was able to center the content correctly.

Filtering Games: The filtering functionality was a bit tricky at first. I had to use the filter() method in JavaScript to create the logic for the "Show Funded Only" and "Show Unfunded Only" buttons, and make sure the page displayed the filtered results as expected.

## License

    Copyright [2025] [CODEPATH]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


