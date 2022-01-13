# Motion-Estimation-Jupyter

A demo can be found here https://www.youtube.com/watch?v=9uyCmfPnyZY

An implementation of the Block-Matching Algorithm using Jupyter Notebook. Draws in arrows into videos that correlate with the velocity of movement within the video. Can be used to determine movement within videos or for compression purposes.

INSTRUCTIONS

1. All imported libraries are in the first cell. Make sure you have all libraries installed. You can install a library by running "!pip install _______ (e.g. !pip install numpy)
2. Put directory of video down in cell 2
3. Run Cell 3 to collect frames from video, creates a folder called "frames_A1". 
4. Run all cells, can change hyperparameters in cell 8
	- Levels determines how many neighbouring blocks the program will search for (1 = 9 blocks, 2 = 16 blocks, etc.)
	- Block width determines dimensions of blocks
	- Threshold of SSD (Sum of Squared Differences) accepted. The higher the value, the less movement the program tracks, and vice versa.
5. Run final cell, generates video named "motion_estimation_vid.mov.
