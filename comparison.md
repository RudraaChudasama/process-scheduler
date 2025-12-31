# Scheduling Algorithm Comparison

| Algorithm | Preemptive | Advantage | Disadvantage |
|---------|------------|----------|--------------|
| FCFS | No | Simple to implement | Long waiting time |
| SJF | No | Minimum average waiting | Starvation possible |
| Priority | No | Important tasks first | Low priority starvation |
| Round Robin | Yes | Fair scheduling | Context switching overhead |

Round Robin performs better in time-sharing systems, while SJF minimizes waiting time when burst times are known.
