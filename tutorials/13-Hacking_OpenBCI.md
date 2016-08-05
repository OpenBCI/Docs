# Hacking OpenBCI


### Getting started

Download [Processing](https://processing.org/download/), the software the OpenBCI GUI is built on. 

Download or (if you are familiar with doing so) clone our [Github repository](https://github.com/OpenBCI/OpenBCI_GUI_v2.0). Open the .pde files from this folder in Processing and start playing with them!

### Ideas and cool code

Want some ideas of how to play with the OpenBCI GUI? Check these out:

 * [Brain-controlled shark attack](http://eeghacker.blogspot.com/2015/03/brain-controlled-shark-attack.html)
     - In this hack, 5 people merge minds to control an RC floating shark using alpha brain waves.
 * [SSVEP labyrinth game](https://harariprojects.com/2015/03/16/brainihack-2015-blue-gsd-with-brain-controlled-labyrinth-game/)
     - In order to win the game, you have to focus on flashing lights that affect your brain waves, and move a ball through the labyrinth. This technique is known as Steady State Visual Evoked Potential (SSVEP).
 * EMG-controlled Flappy Bird
     - [Easy Flappy Bird](https://github.com/niyathic/flappybird_easy) (worked with this to test the game)
     - [Code](https://github.com/niyathic/OpenBCI_GUI_v2.0/tree/EMG_Flappy_Bird) for controlling the above with hand flaps
     - Simply run the two codes and press the up arrow in the GUI to initialize the Flappy Bird function. Bring the game on top of the GUI and flap your hands as the bird does. The electrical activity from your hands will translate into a space bar press, which causes the bird to flap in the game. This was created to work with a specific person's flap, and can be recoded for someone else.
 * [TransAtlantic Biodata](http://bcimontreal.org/transatlantic-biodata-communication/)
     - Controlling someone's muscles over the internet...from across the Atlantic!
 * [Open Bionics robotic arm integration](https://github.com/cfausn/Main/tree/master/personal%20projects/OpenBCI/OpenBionics/OpenBCI_GUI)
     - Using the EEG headset, jaw clenches, and brow furrows, this code works with an Open Bionics arm to move its fingers.
 * [Motor imagery](http://blog.jfrey.info/2015/03/03/openbci-motor-imagery/)
     - Recording signals from the motor cortex.
 * [Brain-controlled helicopter] (https://irenevigueguix.wordpress.com/2016/07/14/a-toy-helicopter-throttle-controlled-by-alpha-waves/).
     - Controlling a helicopter's flight with alpha waves.
 * [Control Your Smartphone By Winking](http://openbci.com/community/hack-the-brain-uk-control-your-smartphone-by-winking/)
     - The app allows the user to map each eye wink (right or left) to a specific action to control a smartphone.
 * [WakeCap](http://openbci.com/community/wakecap-obci-based-device-for-drowsiness-detection/)
     - This project, just awarded $100,000, is in the process of designing a drowsiness detection headset.

### Notes

Much of what you will want to work with in the GUI code is in DataProcessing_User.pde. Here you will find filtered data, pre-coded peak finders for left and right eye blink detection, and more. With these ideas in mind, get coding, and be sure to keep the world updated on what you're doing with the [Community page](http://openbci.com/community/)!