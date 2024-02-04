# WEB102 Prework - *Sea Monster Crowdfunding*

Submitted by: **Thanh Huy Tu**

**Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **3** hours spent in total

## Required Features

The following **required** functionality is completed:

* [ ] The introduction section explains the background of the company and how many games remain unfunded.
* [ ] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [ ] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [ ] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] Centered text throughout the program
* [ ] Added favicon
* [ ] Added CSS effects for "Show Unfunded Only", "Show Funded Only", and "Show All Games" buttons

## Video Walkthrough

Here's a walkthrough of implemented features:

<blockquote class="imgur-embed-pub" lang="en" data-id="a/jRY9bLP"  ><a href="//imgur.com/a/jRY9bLP">Web102 - Sea Monster Crowdfunding</a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>

<!-- Replace this with whatever GIF tool you used! -->
GIF created with ScreenToGif  
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

There was a part when using filter() to filter GAMES_JSON for the list of unfunded and funded games, 
directly return the comparision between element["goal"] and element["plegded"] would return false regardless.
However, this issue disappeared when storing them in two separate variables and compare those variables.

## License

    Copyright [2024] [Thanh Huy Tu]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
