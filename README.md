# _Pokégotchi_

#### _Asynchrony and APIs practice for Epicodus_, _10 Feb. 2020_

#### By _**Jamison Cozart, Michelle Morin**_

## Description

_This application simulates taking care of a pokemon, making sure it gets enough sleep, eats enough food, and gets enough play time. The projects focused on learning and understanding asynchrony, as well as setTimeout and setInterval functions._

## Specifications:

| Specification | Example Input | Example Output |
| ------------- |:-------------:| -------------------:|
| Webpage creates new tamagotchi object | player presses start after selecting animal type | new tamagotchi created |
| Webpage decrements food level every minute | minute passes by | food level one level lower |
| Webpage decrements sleep level every 30minutes | 30min passes by | sleep level decreases by 1 |
| Webpage decrements tamagothci happiness level when not played with for an hour | hour passes by without pressing play button | happiness level decreases by 1 |
| When user presses feed button, food level fills up to full | press feed | food level 100% |
| When user presses the sleep button, sleep level refills | press sleep | sleep level 100% |
| Tamagotchi stays asleep for 30min | press sleep | tamagothci sleeps |
| Tamagotchi happiness level refills when user presses play button | press play | happiness level 100% |
| User cannot press play within 30min of pressing the feed button | press feed | cannot press play for 30min |
| User cannot feed tamagothci while sleeping | press sleep | cannot press feed for 30min |
| When two of the three status bars reach 0, tamagotchi dies | happiness 0% | death |
|After tamagotchi dies, user cannot feed, sleep, or play with it|press play|sorry, the tamagotchi is dead.|
|If tamagotchi is dead, user can restart|Tamagotchi = dead, user presses restart|Refill all stats to 10 and revive life of Tamagotchi|


## Setup/Installation Requirements

#### Node install

###### For macOS:
_If Homebrew is not installed on your computer already, then install Homebrew by entering the following two commands in Terminal:_
* $ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
* $ echo 'export PATH=/usr/local/bin:$PATH' >> ~/.bash_profile

_Install Git with the following command:_
* $ brew install git

_Next, install Node.js by entering the following command in Terminal:_
* $ brew install node

###### For Windows:
_Please visit the [Node.js website](https://nodejs.org/en/download/) for installation instructions._


#### Install this application

1. Clone the repository into preferred directory:
    ```
    git clone https://github.com/jamisoncozart/Tamagotchi
    ```
2. Change directories into the project directory:
    ```
    cd Tamagotchi/
    ```
2. Install all dependencies listed in the package.json:
    ```
    npm install
    ```
3. Run the start script to Lint, Build, and Start the live server, and the webpage will open automatically in your default web browser
    ```
    npm run start
    ```

## Technologies Used

* HTML
* CSS
* Javascript
* Webpack
* Jest
* Git
* Babel
* ESLint

### License

*This webpage is licensed under the MIT license.*

Copyright (c) 2020 **_Jamison Cozart, Michelle Morin_**
