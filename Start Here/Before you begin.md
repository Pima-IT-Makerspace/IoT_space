# Before you begin

Below are some of my thoughts as I worked through some of the projects in the kits.  I hope that they’ll help you avoid some of the headaches I ran into in trying to put them together.


There are two kits available to work with.  [SunFounder](https://docs.sunfounder.com/projects/kepler-kit/en/latest/index.html) and [KeyeStudio](https://wiki.keyestudio.com/KS0361(KS0365)_keyestudio_37_in_1_Starter_Kit_for_BBC_micro:bit).  These links take you to the provided projects for their respective development kit.


The provided breadboards might not be a 1:1 match for what’s on the docs/walkthroughs.  I’m not sure if parts might have been swapped since the making of the diagrams but it’s pretty confusing when you just start learning!  


The diagram on the left was provided by SunFounder and the board on the right was what was included in the kit.  The biggest points of frustration with this kit are that the positive/negative voltage rails are flipped and, as a result, the numbering system completely breaks apart.  This leads to having to manually count terminals to figure out where you need to plug in your cables.  


As long as the rails match up with the diagram, everything should work!  Ignore the numbers - they’ll only bring you more grief.


Required firmware for some projects is not always included!  You might run into moments where you’ll have to dig through GitHub repositories and find missing firmware to get your device to work - it happened to me with getting the LCD screen to work in the SunFounder kit.  Think of it as a learning opportunity. :) 


When working with the SunFounder Kit, you have the choice of working with MicroPython (Python for microcontrollers) and Arduino (C for microcontrollers).  I would recommend starting with MicroPython as it is more beginner friendly and has much more support compared to Arduino (all of the IoT-specific projects only provide Python files).


When working with MicroPython, you’ll be primarily using Thonny to modify/upload your Python code.  With Arduino, you’ll be using Arduino IDE.  Both function relatively similarly so jumping between the two won’t be too confusing.


Using your own code editor/uploader like VSCode is theoretically possible but choosing to do so means signing up for your own micro-project before working on the projects provided here.  By all means, feel free to do so - it’s a great way to learn!  But that’s currently beyond the scope we’re shooting for with this MakerSpace.  If you do so, make a guide and help teach others!



The MicroBit board supports Arduino and their own code editor that lets you program by moving code “blocks” around.  This is what it looks like:



If you struggle with understanding programming, this might be an easier entry into it.  I haven’t personally touched it yet but it seems like a good way to be introduced to programming concepts without having to touch it yourself.



You may run into issues with IoT projects if they require a particular port to be opened - this is likely an issue with the network that the device is connected to and does not mean that you’ve done anything wrong.  If this happens, don’t be afraid to ask questions and get to the bottom of it!
