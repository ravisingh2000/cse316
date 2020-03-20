# cse316
Ques. 5. CPU schedules N processes which arrive at different time intervals and each process is allocated the CPU for a specific user input time unit, processes are scheduled using a preemptive round robin scheduling algorithm. Each process must be assigned a numerical priority, with a higher number indicating a higher relative priority. In addition to the processes one task has priority 0. The length of a time quantum is T units, where T is the custom time considered as time quantum for processing. If a process is preempted by a higher-priority process, the preempted process is placed at the end of the queue. Design a scheduler so that the task with priority 0 does not starve for resources and gets the CPU at some time unit to execute. Also compute waiting time, turn around.

Solution:- In Priority_round_robin.cpp the code implements priority based Round robin algorithm in which the after a particular Time Quantum the process preemption occurs and the process with the highest priority in the queue will get the chance to use the CPU.
test case input: total number of process :4 time Quantum :2 Arival burst priority 1 2 3 3 2 1 4 5 6 6 5 4
Expected output: Average Waiting time: 3.25 Average Turnaround Time: 6.75
