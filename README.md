# CPU-Scheduling-Algorithms
An implementation of various CPU scheduling algorithms in C++. The algorithms included are First Come First Serve (FCFS), Round Robin (RR), Shortest Process Next (SPN), Shortest Remaining Time (SRT), Highest Response Ratio Next (HRRN), Feedback (FB) and Aging.
## Input Format
Line 1: "trace" or "stats"

Line 2: a comma-separated list telling which CPU scheduling policies to be analyzed/visualized along with their parameters, if applicable. Each algorithm is represented by a number as listed in the introduction section and as shown in the attached testcases. Round Robin and Aging have a parameter specifying the quantum q to be used. Therefore, a policy entered as 2-4 means Round Robin with q=4. Also, policy 8-1 means Aging with q=1.
1. FCFS (First Come First Serve)
2. RR (Round Robin)
3. SPN (Shortest Process Next)
4. SRT (Shortest Remaining Time)
5. HRRN (Highest Response Ratio Next)
6. FB-1, (Feedback where all queues have q=1)
7. FB-2i, (Feedback where q= 2i)
8. Aging

Line 3: An integer specifying the last instant to be used in your simulation and to be shown on the timeline.

Line 4: An integer specifying the number of processes to be simulated.

Line 5: Start of description of processes. Each process is to be described on a separate line. For algorithms 1 through 7, each process is described using a comma-separated list specifying:

1. String specifying a process name
2. Arrival Time
3. Service Time

Note: For Aging algorithm (algorithm 8), each process is described using a comma-separated list specifying:

1. String specifying a process name
2. Arrival Time
3. Priority

Processes are assumed to be sorted based on the arrival time. If two processes have the same arrival time, then the one with the lower priority is assumed to arrive first.


## TestCases

### Testcase 1

![image](https://github.com/user-attachments/assets/1583f05e-7092-4b1a-8281-268bdfa6ef1e)                                    ![image](https://github.com/user-attachments/assets/ee7df2c4-2376-454c-a36c-eb480a81d634)

### Testcase 2

![image](https://github.com/user-attachments/assets/72f7620a-4a3c-4d9f-85de-17262f3a10d0)                                    ![image](https://github.com/user-attachments/assets/85c181c6-2546-42fe-bd87-04164a965c6a)

### Testcase 3

![image](https://github.com/user-attachments/assets/b0e391c2-2f63-4172-b533-f1c9ded8102f)                                    ![image](https://github.com/user-attachments/assets/e025becc-40d7-431e-824a-2b63d47d97d5)

### Testcase 4

![image](https://github.com/user-attachments/assets/f0c18c4a-3157-4a2d-bcab-73f5797c34bf)                                    ![image](https://github.com/user-attachments/assets/b9bad4f8-5bfe-4cd6-b4eb-92db491992f6)

