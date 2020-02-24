## Context switch:
### Is the process or tecnique of storing the state of a process or thread, with the intention to restore and resume the execution later.
### Context switch can also occur when an interrupt happens for example: a program requesting for disk storage access
### When a scheduler decides to change which task is running this is a "context switch"
## Objective:
### Allows multiple processes to share a single CPU (multitasking OS)
## Multitasking OS
### Concurrent execution of multiple tasks or processes over x period of time. This is done by new tasks interrupting olw tasks before they finish instead of waiting for them to end. This results in the CPU executing multiple tasks in an interleaved manner (intercalado)
## Context switch cost
### Context switches are expensive and much of the design of an OS is focused on economize their computation. Switching from one context to another requires time for: administrating, saving and loading registers and memory maps (tables and lists). 
## Task
### quasi-independent program, shares CPU time with other tasks that are controlled bu the task manager.
## task context saving
### When a task is rescheduled (interrupted by another task or multitasking) the set of registers need to be saved for later execution. 
## Tick Clock Functionalities
### Time slice scheduler uses the tick count to decide after how much time each task's CPU usage expires.
### common system time 
### rescheduling requirements

