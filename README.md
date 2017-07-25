# Music-Visualizer

This is my music visualizer.  Please make sure you run it in Google Chrome in order to ensure that it works.  This is based off of the audio visualizer found at https://airtightinteractive.com/demos/js/reactive/.  Other libraries involved are Mozilla Development Network's Web Audio API and mrdoob's three.js.  

Press right arrow to skip to the next song
Press space bar to pause/continue
Mousewheel to zoom in/out

Current Bugs involved:

-  Not proceeding to the next song
-  Not looping at end of playlist
-  Cutting off songs early
-  not unpausing/loss of audio
-  Audio/Animation synchronization (specifically with the inner sphere)
-  Incorrect audio being played after repeated skips


These bugs typically happen if you attempt to push any of the buttons. If you just load audio in and let it run, then it will work perfectly fine.
