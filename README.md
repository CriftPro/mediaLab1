# mediaLab1

-- UPDATED-- 

Instruction to launch:
We used node js to lauch the scripts.
1)Download node js packages.
2)Download the project file.
3)Open the console
4)Open project directory in console
5) Type :
node start_server.js
6) Go to your localhost address, port 8080
7) See the webpage.

Testing results:
Tested in mozzila firefox v112.0 and micrsoft edge v112
Works as intended.

Implemented functions:
Player
Button play,pause,stop, forward by 5, back by 5.
Playlist ( but only m3u8 format)
Load button

Playlist working:
Input the link to the m3u8 video.
Click Load
Player now will show linked video.

LAB DESCRIPTION:

This lab aims to build your first HTML5 live stream (HLS) player.

There are many open source alternatives. You can try to use as Video.js player as a startup: https://github.com/videojs/video.js
or try a live example: https://jsbin.com/gejugat/edit?html,output

# Requirements for repository
  - You have to clone this repository and make two branches (master and develop).
  - The develop branch should contain commits of every new feature of the player.
  - When all features will be ready you have to merge the development branch to the master.

# Requirements for player
  - You have to find an HLS player and embed it into index.html file.
  - The player should be able to run "Big Bunny" video from this URL: https://video-dev.github.io/streams/x36xhzz/x36xhzz.m3u8
  - If player fails to play "Big Bunny" try this stream: https://d2zihajmogu5jn.cloudfront.net/bipbop-advanced/bipbop_16x9_variant.m3u8
  - Implement at least three features in the index.html (Play, Pause, Stop, Jump to 5 sec forward, Jump to 5 sec backward, Playlist, Shuffle).
  - Test player on at least two browsers and specify in README.md which version and browser it was.
  - Additional features are welcome and bonuses are available.
  - To pass this lab, you have to complete at least two points from the requirement list.

