**Assignment #1: OS Scheduler**
Implement a simple OS scheduler using CPP. The scheduler’s task is to receive a set of processes and their details and then decide the order of executing these processes
based on the chosen algorithm. Finally, the scheduler will output the order of process execution, in addition to some stats about each of the processes.The scheduling algorithm chosen for this assignment will be a slightly modifed version Shortest
Remaining Time (SRT) algorithm. In the assignment, we make a slight modification such that we give more priority to the process that arrived later, which is the opposite of
what we learned in class. In the case where processes have the same remaining time and arrival time, we choose the process that had its name listed first in the input file.
