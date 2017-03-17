# Multi-Level-Feedback-CPU-Process-Sheduling-with-Graphical-User-Interface-GUI-
Multi Level Feedback CPU Process Scheduling with Graphical User Interface(GUI).
There are Three levels of Priority in total.
In First level Queue of Processes Each process is assigned a round robbin time of 10ms.
In Second level Queue of Processes Each process is assigned a round robbin time of 20ms.
In Third level Queue of Processes Each process executes till completion based on First Come First Serve.
When a Process is arrived it moves to Queue Q0
In Q0 the process runs until its completion but not more than 10ms,if the process is not completed with in 10ms it is moved to Queue Q1. 
In Q1 the process runs until its completion but not more than 20ms,if the process is not completed with in 20ms it is moved to Queue Q2.
In Q2 the process runs until its completion.
The processes in Q1 executes only when the processes in Q0 are empty.
The processes in Q2 executes only when the processes in both Q0 and Q1 are empty.
Each process should be created with following information
1)Process ID
2)Process Burst Time
3)Process Arrival Time
The process creation can be done in two ways
one way is first user needs to enter the following data
1)Number of Processes
Then for each process the following information 
1)Process ID
2)Process Burst Time
3)Process Arrival Time
Other way is user needs to enter the following data
1)Number of Processes
2)Process Burst Time Range
3)Process Arrival Time Range
Then the program creates processes randomly.
After Completion of all Processes following information needs to be tracked
1)Process Start Time
2)Process Response Time
3)Process Completion Time
4)Process Turnaround Time
5)Process Waiting Time
Formulae:
