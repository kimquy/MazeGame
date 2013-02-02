MazeGame
========

This is a simple game I created in CS210 class. I implemented this game in Unicon,
a programming language created by Dr Jeffrey (http://unicon.sourceforge.net).

You can play this game by using arrow key. Or you can let it play by itself which is 
auto mode. I implemented a backtrack algorithm to help the character escape from the
monster

BackTrack Algorithm
==================

The character will check every spot which he never been to. If he stuck he will go 
back to the last spot which there is one or more way to go. Otherwise he never escape,
and the monster will eat him !!!

Sample Output
=============

![Alt text](./sampleOutput/1.png)

![Alt text](./sampleOutput/2.png)

![Alt text](./sampleOutput/3.png)

![Alt text](./sampleOutput/4.png)
