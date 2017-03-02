To run the program, cd to the directory and use the following command:

python3 ball_tracking.py -v "the video's path"

It requires python3, imutils, and opencv3

Currently it is set to 5 frame per second, to change fps, simply change the wait time (ms) in the following command at the bottom of the code (line 103):

key = cv2.waitKey(200) & 0xFF

