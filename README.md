
# Submission for 18CSC302J - Computer Networks
<!--This is a **fully featured chess app** written purely in Python using Pygame Library.
-->
![main image](screenshots/main.jpg)

<!-- Click [here](screenshots/screenshots.md) to see more few screenshots of My-PyChess in action!
 -->
<!-- Any bug-reports, suggestions or questions, you can leave it in the github issues section.
If you want to directly communicate with me, you can mail me: itsankith26@gmail.com

The My-PyChess project is available under MIT License. The MIT Licence applies to all the resources I have created in this project. This includes all the python files and text files. But some resources(images, sounds and font file) are not created by me, I have downloaded these from the internet. I have given credits to the authors of these resources in [this file](res/CREDITS.txt). All these resources maintain the original licenses that the authors have leased them under (These licenses permit my use of the respective resources in this project). -->

<!-- ## Getting started, with python source code(All OS support)
- Make sure you have **python** and **pygame** installed and working.
- Clone this repository (or download zip file and extract it).
- Then, run the **pychess.py** file. Trying to run any other file will not run the game.
- Those who are running older versions of this app, can upgrade to the latest version by the same method.

## Getting started, by downloading executable(Windows OS only)
- If you are only interested in chess and not python programming, head to releases section on github. 
- There, you will find executable packages under the respective versions. 
- Download the My-PyChess-win-exe.zip from the latest version, extract the folder into your computer.
- Run My-PyChess.exe
- Those who are running older versions of this app, can upgrade to the latest version by the same method.

Interested in python game development with pygame and want to learn from this applicaton - I have released a [lite implementation](https://github.com/ankith26/My-PyChess-lite/) of My-PyChess, that focuses just on chess programming - free from all the code for menus, singleplayer, online etc. 
 -->
 
<!-- ## Features
- Clean GUI with a lot of menus for ease of use.
- Allows users to make only valid moves and follows all traditional rules of chess.
- Playable between two clients over the server via TCP-IP connection.


## Team Members
- Abhigyan Singh RA1911003010607
- Advaith Suresh RA1911003010604
- Kusum Grandhi RA1911003010597
- Suraj Mishra RA1911003010611
-->
<!-- 

Click [here](CHANGELOG.md) to see full changelog. -->
<!-- 
## Online Gameplay
- You can self-host the My-PyChess online server(read more [here](onlinehowto.txt) ).
- Apart from that, I have launched a public My-PyChess server for PUBLIC BETA TESTING, which ANYONE in the world can connect to.

- Caveat: The server is on a IPv6-only network. This means that your network MUST SUPPORT IPv6 to connect. If your network does not support IPv6, try any other internet network. In my experience, many mobile networks are supporting IPv6 technology, so try mobile network tethering/hotspots. -->

<!-- ### How to test wether your network supports IPv6
- A reliable way to test would be to enter "ipv6.google.com" in the browser window. If google pops up, then IPv6 is working for you. -->
<!-- 
## How to customise the game using preferences
- In the main game menu, click preferences.
- Hover over each name to know more about them.

1. Sounds: When True, sounds are enabled.
2. Flip: When True, it shows the chess board from the perspective of the player who is playing, otherwise shows a constant board with white side at the bottom.
3. SlideShow: When True, it will show a slideshow of images on main menu.
4. Show moves: When True, it will show all legal move options for a selected piece during gameplay.
5. Undo: When True, it allows users to undo.
6. Show Clock: When True, it shows a clock in multiplayer chess mode when timer is disabled, clock displayes total time elapsed since start.

- You can also open res/preferences.txt and edit the file to your preferences

## What's Next
- I prefer to work on this app locally, I do not commit to github for every change I make. I only commit when a new version is available or when I update any readme, etc.
- For the next version (v3.3), I plan to release less of new features and focus on the GUI along with any bugfixes or performance improvements. Mainly because v3.2 has come with a lot of code refactoring, new features and changes to the backend, and GUI hasn't recieved much attention by me in this release.
 -->
# My-PyChess: A Python-Pygame Chess Application

## Overview
My-PyChess is an interactive chess application developed using Python and Pygame. The application features a user-friendly main menu, online gameplay options, and various user preferences. It showcases advanced programming concepts like socket programming, multi-threading, and GUI development in Python.

## Key Features
- **Interactive Main Menu**: Utilizing Pygame for graphical interface and event handling.
- **Online Gameplay**: Ability to play chess online with other players.
- **User Preferences**: Customizable settings for slideshow backgrounds and sound.
- **Logging and Server Management**: Server script for handling online gameplay with features like player statistics, game requests, and player kick-out options.

## Technical Components
- **Pygame for GUI**: Main menu and game interfaces are built using Pygame.
- **Socket Programming**: For online multiplayer functionality.
- **Threading**: Managing different aspects of the game and server simultaneously.
- **Logging**: Advanced logging for debugging and monitoring server activities.

## How It Works
1. **Main Menu**: Displays options like Online Play, Preferences, and About. Uses Pygame for rendering buttons and handling user inputs.
2. **Online Gameplay**: Connects players through a server using sockets, enabling online matches.
3. **User Preferences**: Offers customization such as background slideshow and sound settings.
4. **Server Script**: Manages online connections, game sessions, and player activities.

## Installation and Usage
1. Clone the repository.
2. Install Python and Pygame.
3. Run the main file to launch the program.
4. For online play, run the server script.

## Future Enhancements
- Adding AI opponents for solo play.
- Improving the GUI for a more engaging user experience.
- Implementing chat functionality in online mode.

## Limitations
- Requires a stable internet connection for online gameplay.
- Limited to chess gameplay; future versions could include other board games.

## Team Members
- Abhigyan Singh RA1911003010607
- Advaith Suresh RA1911003010604
- Kusum Grandhi RA1911003010597
- Suraj Mishra RA1911003010611
---

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pygame](https://img.shields.io/badge/Pygame-0175C2?style=for-the-badge&logo=pygame&logoColor=white)
![Multiplayer](https://img.shields.io/badge/Multiplayer-00C853?style=for-the-badge)
![Chess](https://img.shields.io/badge/Chess-D32F2F?style=for-the-badge)

*Note: The stickers are for visual representation only and do not imply any official endorsement.*
