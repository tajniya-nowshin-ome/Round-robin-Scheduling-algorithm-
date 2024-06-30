# Round-robin-Scheduling-algorithm-

Lab Report: Implementation of Round Robin (RR) Scheduling Algorithm.

Introduction:
The Round Robin (RR) algorithm is a preemptive CPU scheduling technique where each process is cyclically assigned a fixed time quantum. 
It treats the ready queue as a FIFO queue, allowing every process to access the CPU for a specified time slice.

Objective:
To implement the Round Robin scheduling algorithm and evaluate its performance.

Implementation Details:
Declare the array size to store process details.
Assign a fixed time quantum (also known as the time slice).
Processes are added to the ready queue in the order they arrive.
The CPU executes each process for the specified time quantum.
If a process doesn’t complete within the time quantum, it is moved to the end of the queue.


Advantages:
Fairly distributes CPU time among processes.
Suitable for time-sharing systems.

Disadvantages:
Overhead due to context switching.
May not be optimal for certain workloads.

Conclusion:
Round Robin provides predictable behavior and ensures that no process monopolizes the CPU for too long. 
However, adjusting the time quantum is crucial to balance responsiveness and efficiency.
