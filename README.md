CPU SCHEDULING SIMULATOR

A web-based simulator for visualizing and comparing CPU scheduling algorithms, built for Operating Systems coursework and demonstrations. The simulator allows users to manually input or randomly generate process data and observe how different scheduling strategies affect execution flow, waiting times, and turnaround times.
Featuring real-time Gantt chart generation, step-by-step simulation, and performance metrics, this tool provides a hands-on way to understand and compare scheduling behaviors such as FCFS, SJF, SRTF, Round Robin, and Multi-Level Feedback Queue (MLFQ).
Designed for educational clarity and interactivity, this simulator runs entirely in the browser — no installations or servers required. Ideal for students, instructors, and anyone learning how operating systems manage CPU scheduling.

To use the CPU Scheduling Simulator, start by clicking the “Random Processes” button. This will automatically generate a set of five random processes, each with a unique arrival time and burst duration. These serve as input data for testing the scheduling algorithms.

Next, choose a scheduling algorithm from the dropdown menu. The available options include:

First Come First Serve (FCFS) – executes processes in the order they arrive.

Shortest Job First (SJF) – selects the process with the shortest burst time.

Shortest Remaining Time First (SRTF) – a preemptive version of SJF that picks the process with the least remaining time.

Round Robin (RR) – processes are executed in fixed time slices using a cyclic queue.

Multi-Level Feedback Queue (MLFQ) – processes are moved across different queues based on their behavior and time quantum.
