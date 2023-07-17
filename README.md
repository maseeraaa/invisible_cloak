This is a python script which uses an image processing technique called color detection and segmentation.
The basic idea is given below:

Capture and store the background frame.
Detect the red colored cloth using color detection algorithm.
Segment out the red colored cloth by generating a mask.
Generate the final augmented output to create the magical effect.

The algorithm is very similar in principle to green screening. But unlike green screening where we remove the background, in this application, we remove the foreground!
We use a red-colored cloth as our invisible cloak (colors like green or blue will also work fine with a little bit of tweaking)
