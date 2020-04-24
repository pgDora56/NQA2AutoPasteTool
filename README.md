# NAPT

NQA2 Automatically Paste Tool

Automatically paste and send the copied song information etc. at the time of questioning in NQA2

## Usage 

The title bar color changes to darkblue(player)/sienna(provider) when this script is running.

Clicking title(`Nagaya Quiz Arena 2 with NAPT`), You can go back and forth between `player` and `provider`.

All operation is moved from keydown when you are provider.

|Key|Operation|
|-|-|
|Space|Paste from clipboard & Send that data for chat|
|Q|Correct|
|W|Wrong|
|E|Through|
|Shift+R|Go to next game in same rule|
|F|Increase player's freeze count to max(9) after select player|
|Alt+R|Score fix - Pseudo NY rule|


## Operation confirmed environment

* Chrome 
* Chromium browser 

Firefox is not ready.....

## Setup

1. Install [Tampermonkey](https://www.tampermonkey.net/) in your browser
2. Click [napt.user.js](https://github.com/pgDora56/NAPT/raw/master/napt.user.js)

## LICENSE 

MIT
