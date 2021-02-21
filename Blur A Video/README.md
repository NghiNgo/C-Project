# Things to know:

(1) The code will only compile in Linux environment.

(2) To run in windows, please use the file: ‘blur_video.o’ and run it in cmd. However if it does not run(problem in system architecture) then compile it in windows by making suitable and obvious changes to the code like: Use <iostream.h> in place of <iostream>.

(3) Compile command: g++ ­w blur_vid.cpp ­o blur_vid `pkg­config ­­libs opencv`

(4) Run command: ./blur_vid

(5) The video Bumpy.mp4 has to be in the same directory as the code.

Before you run the code, please make sure that you have OpenCV installed on your // system.