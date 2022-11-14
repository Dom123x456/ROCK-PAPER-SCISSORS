# Rock, paper, scissors
[Live site](https://11bus11.github.io/lizard-spock-extension/)

This game is an extension of the classic Rock, paper, scissors game. This extension is used in the tv-show The Big Bang Theory. The additions in this version are "lizard" and "spock" (from Star Trek The Original Series). The rules copied from [The Big Bang Theory Wiki](https://bigbangtheory.fandom.com/wiki/Rock,_Paper,_Scissors,_Lizard,_Spock) are:


## UX - User Experience

### User stories
I want the user to:
- Play an entertaining game.
- Be able to choose how many points are needed to win a round.
- See the rules at all times.
- See scores and choices each round.

### Colour
I chose a dark blue colour and black for the backgrounds. The instruction page has a black background, and the page where you play the game has a dark blue one. The "game-window" has a black background with a light blue border to make it look like a screen inspired by Star Trek TOS (the original series). The buttons are either blue or red. Red is for the different choices, and blue is for the rest of the buttons. All text is white.
![Colours main](assets/media/Spock_main_colours.png)
![Colours buttons](assets/media/Spock_buttons_colours.png)


#### Structure
For the layout of the page, I chose to create a game window with a border around it. This is how a lot of remakes of older games look. The window is also shaped with round corners, just like the screens in Star Trek. I chose to have the rules accessible at all times due to this version/extension of the classic "Rock, paper, scissors" game. 
#### Typography
The font I chose is called Orbitron (the san serif version, since it is easier to read on a screen). The letters are shaped the same way they were in older games, but less pixelated. This gives the game a retro feel while not looking too old and pixelated. I found the font on 

## Features
The game is simple with one starting page and one game page with 3 windows. One window for choosing how many points is needed to win a game, one for the game itself, and one for the result of the game. 

### Starting/instruction section
This page was made to give the user instructions on how to play the game. In some games, especially older ones, you are not given all instructions on how to play the game. It is a lot of trial and error. Even if I want to give this game a retro feel, this is one of the things I do not want to replicate. An instruction page also keeps the user from getting frustrated and/or annoyed.
![starting page](assets/media/start_comp.PNG)


### Game window
When the user has chosen the points needed to win, they play the game itself. This is done on this window. When you choose one of the options you get to know who won the round and the winner gets one point. Then you click continue to play another round. this continues until you or the computer have enough points to win. When that happens the continue button sends you to the result window.
![Game window](assets/media/game_comp.PNG)


### Rules
The rules are displayed as long as you are on the game.html page. Depending on which device you are on the placement might be a bit different, but the rules are always accessible. This is to avoid confusion since this game is from a tv-show that not everyone has seen. By always showing the rules I can avoid the user getting confused about why for example spock wins against rock. The information is right there and the user can understand the logic. 


### Features left to implement
- I would like to add some more choices that the user can make.
- And maybe make it possible for the user to play against a friend IRL.

## Testing

### Device testing
The game has been tested on multiple devices using the Mozilla dev tools. These are the devices:
- iPhone SE (2:nd generation)
- iPhone 11 (Pro + Pro Max)
- iPhone 13 (Pro Max + Mini)
- Samsung Galaxy Note 10
- Samsung Galaxy S10/S10+
- Samsung Galaxy S20
- iPad

The game was also tested (natively) on these devices:
- iPhone SE (2:nd generation)
- Samsung Galaxy S9
- iPad
- ACER Aspire 5 15-inch (laptop)
- Desktop computer (Windows 10)


### Peer review
I asked some people I know to test the game. They found some small issues with the media queries but did not find much wrong with the game logic.
One of the people I asked said that they liked the retro style of the game. Another person said it would be nice to get some feedback on how many points are chosen. This was later implemented.

### Game logic testing
I tested the game logic multiple times. The part where your choice and the computer's choice are compared was tested the most. Each possible combination was tested to make sure the result was correct. Every other part of the game was tested similarly.

### Validator testing
#### Code
- Put the JavaScript through jshint. It came up with some warnings. I had forgotten some semi-colons and had added some in places it was not needed. This is now fixed. No errors left.
- The CSS was validated in the official Jigsaw validator. No problems were found.
![CSS validation](assets/media/spock_css_validation.PNG)
- The HTML was tested in the w3c validator. No problems were found.
![HTML validation](assets/media/spock_HTMLgame_validation.PNG)
![HTML validation](assets/media/spock_HTMLindex_validation.PNG)

#### Lighthouse
This was the lighthouse result:
![Lighthouse](assets/media/spock_lighthouse.PNG)

#### Contrast and more
I checked all colours in the [accessibility checker](https://www.accessibilitychecker.org/color-contrast-checker/). Their colour contrast checker tells you if the background and foreground (the text) have a large enough contrast. If it does not have enough contrast, it will be very hard for people with bad eyesight to read.
- Validation for the dark blue background.
![dark blue background validation](assets/media/dark_blue_contrast.PNG)
- Validation for the black background.
![black background validation](assets/media/black_contrast.PNG)
- Validation for the blue buttons.
![blue button validation](assets/media/blue_contrast.PNG)
- Validation for the red buttons.
![red button validation](assets/media/red_contrast.PNG)

### Fixed bugs
- 

### Deployment
This game was deployed to github pages.

- Open the repository settings.
- Go to "pages" (found under "code and automation").
- Choose which branch to build from. You want to choose "main". Do not forget to save the settings.
- (If needed, choose a custom domain)
- Open the repository in github desktop (I used github desktop. You can do this in git too.)
- Choose to create a local clone (the first time you open your repository in github desktop, there should be a window asking if you want to create a clone)
- Copy the link to your deployed website (which can be found in the github pages settings, where you chose which branch to build from) and make sure it is operating as expected.
- The deployed website will now be updated when you push anything new to the repository.

#### Forking and cloning
- Forking is creating a new repository with the same content as the one you forked. 
    - This is done by going to the repository you want to clone, and clicking the "fork" icon in the top right corner.
- Cloning is used for making local copies of your code.
    - Cloning a repository with github desktop is easily done by clicking the green "code" button and choosing the "open in github desktop" option. If you do not have a clone already, github desktop will ask if you want to create a local clone. Click yes.
    - If you do it with git you have to write "git clone" and then specify what you want to clone.


### Credits

