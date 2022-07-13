# Standing-Waves
Pure Data patches to create resonant frequencies in a room

The wave calculator will determine the frequency of all the possible standing waves in a room. You must input the temperature first to determine the speed of sound and then input the dimensions of the room. Then you can click through the Hradios and it will output the frequencies in the first 9 modes.

The notes patch is a recent addition to help with being able to mix the waves together in consonance. It outputs a note name based on what the frequency is closer to in western scale. 

In the Finalized Ideas folder, I created a patch to use a korg midi drum pad and korg midi fader controller to be able to launch the Hradios for live performances. But it is not necessary. It splits the korg into the two rows and the different registers to control different Hradios. In addition I have saved a few dimensions of common places that I used the patch for performance so they can be quickly added.  

At the bottom of the patch there are tables that calculate the harmonics of the axial standing waves.  You first have to calculate the values for all of the longitudinal waves as these are used as the basis for the axial wave values.  

## How to start:
1. Open the 4 channel Korg patch
2. In the middle of the right hand side enter the Length, Width, Height, and Temperature of the room you are in
3. Click every button at the top under Length_Mode, Height_Mode, etc, until all the message boxes are filled
4. Return every button to the first position
5. Click the Tables button and then the Toggle button, if it works you should see the values of harmonics printing out in the console as well as population the graph
6. Turn on the DSP to hear.
7. Turn on the Wave to see the waves in each channel
8. Use the Faders to turn up the volume.  (Remember the fundamental frequency of a room larger than 10m will be sub human hearing range, but will make a great LFO on higher waves)