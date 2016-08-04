# Hacking OpenBCI


### Getting started

Download [Processing](https://processing.org/download/), the software the OpenBCI GUI is built on. 

Download or (if you are familiar with doing so) clone our [Github repository](https://github.com/OpenBCI/OpenBCI_Processing). Open the .pde files from this folder in Processing and start playing with it!

### Ideas and cool code

Want some ideas of how to play with the OpenBCI GUI? Check these out:

 * EMG-controlled Flappy Bird
     - [Easy Flappy Bird](https://github.com/niyathic/flappybird_easy) (worked with this to test the game)
     - [Code](https://github.com/niyathic/OpenBCI_GUI_v2.0/tree/EMG_Flappy_Bird) for controlling the above with hand flaps
     - Simply run the two codes. Press the up arrow in the GUI to initialize the Flappy Bird function. Bring the game on top of the GUI and flap your hands as the bird does. The electrical activity from your hands will translate into a space bar press, which causes the bird to flap in the game. This was created to work with a specific person's flap, and can be recoded for someone else.
 * [Open Bionics robotic arm integration](https://github.com/cfausn/Main/tree/master/personal%20projects/OpenBCI/OpenBionics/OpenBCI_GUI)
     - Using the EEG headset, jaw clenches, and brow furrows, this code works with an Open Bionics arm to move its fingers.
 * [Brain-controlled helicopter] (https://irenevigueguix.wordpress.com/2016/07/14/a-toy-helicopter-throttle-controlled-by-alpha-waves/).
     - Controlling a helicopter's flight with alpha waves.

### Notes

Much of what you will want to work with in the GUI code is in EEG_Processing.pde. Here you will find filtered data, pre-coded peak finders for left and right eye blink detection, and more. With these ideas in mind, get coding, and be sure to keep the world updated on what you're doing with the [Community page](http://openbci.com/community/)!