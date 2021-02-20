# Things to know:

(1) The code will only compile in Linux environment.

(2) To run in windows, please use the file: ‘blank.o’ and run it in cmd. However if it does not run (problem in system architecture) then compile it in windows by making suitable and obvious changes to the code like: Use <iostream.h> in place of <iostream>.

(3) Compile command: g++ -w blank.cpp -o blank `pkg-config –libs opencv`

(4) Run command: ./article

Before you run the code, please make sure that you have OpenCV installed on your system.