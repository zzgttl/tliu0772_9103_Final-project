# tliu0772_9103_Final-project
## Instruction:
press the play/pause button to control the audio playing, move your mouse to control volume, and you can simply refresh the page or adjust the size of the window to generate new version
##Individual approach
My code is driven by audio, the size of elements(flowers, dots) change as the volume changes, the flowers and dots jump while the grass stay static
I used p5.FTT to analyse the amplitude of the audio and drive the size change, while using "map" function to convert the amplitude to a scale value,The display method of both Flower and Dot classes includes a scale parameter, which the based size of elements is adjusted by, then we got a dynamic picture
