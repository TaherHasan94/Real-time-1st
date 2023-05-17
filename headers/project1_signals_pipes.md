﻿<a name="br1"></a>Birzeit University - Faculty of Engineering and Technology

Project #1

Signals & Pipes under Unix/Linux

Due: May 8, 2023

Instructor: Dr. Hanna Bullata

The competition

We would like to create a multi-processing application based on the signals and pipes/ﬁfos

The competition can be explained as follows:

1\. On startup, the parent process will fork the 5 children processes.

2\. The parent process will write down 2 comma-separated integer values in a ﬁle called

3\. Once instructed to do so, the ﬁrst 4 processes will generate 4 ﬂoating values in the

range decided on by the parent. Each process will note down its generated value in

4\. Once the parent process gets the 4 values, it will send them as a message (e.g.

comma-separated message) through a pipe to its ﬁfth child process (the co-processor).

5\. The co-processor will sum the ﬁrst 2 values and create the value Sum1. In addition, it

6\. The parent process decides which team has the higher sum.

7\. The application runs the steps 2 . . . 6 as many times as instructed by the user. If

no argument is provided, assume 5 rounds.

8\. On termination, the parent declares the winner of the competition, kills all its child

processes, removes any allocated resource and exits.

What you should do

• Write the code for the parent and the children. The parent’s code should be written

• Check that your program is bug-free. Use the gdb debugger in case you are having

problems during writing the code (and most probably you will :-). In such a case, compile your code using the -g option of the gcc.

• Use graphics elements from opengl library in order to best illustrate the application.

Nothing fancy, just simple and elegant elements are enough.

• Insert delays between rounds (e.g. few seconds).

• Send the zipped folder that contains your source code and your executable before

the deadline. If the deadline is reached and you are still having problems with your