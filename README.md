# Hand Gesture Detection
The program that I have created is able to detect rock, paper, scissors gestures. Along with these three gestures,
it will have a "start" gesture that allows the computer to start the round.

The detection is done through finding contours and using NCC template matching to detect gestures. First, I created a small region of interest where the contours will be drawn.
Then I gathered four different poses - Rock, Paper, Scissors, and Start - and applied template matching. In order to draw contours, I used skin detection through RGB masking and thresholding values.
 
 ## Requirements
 - Python
 - numpy
 - OpenCv
