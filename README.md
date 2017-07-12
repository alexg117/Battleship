# Battleship
Han, the Battleship AI

This is a Battleship AI that was written for RPI's Intro to AI class. The game itself is in Javascript. Yes, 
I know there are security issues. The class was an AI class, not a web design or security class. 

For the full (working) project please see hanbattleship.co.nf

Data recorded from games is stored on the server. The data is stored in a rather messy way due to the limit on SQL calls
allowed by the host of the subdomain, so I'm not including it here. The code also needs a login mechanism of some sort
to run. This repository only contains the AI's code by itself and lacks many of the external dependencies because, simply
put, it's full of gaping security holes and various other issues. (It does work, when the player doesn't try to exploit it)
