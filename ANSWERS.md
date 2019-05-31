**1. List all of the main states a process may be in at any point in time on a standard Unix system. Briefly explain what each of these states means.**
created: in this state, the process awaits admission to the ready state
read: loaded into memory and wait for execution.
running: instrcutions are executed.
blocked: process can't not advance without further input
terminated: done running or kil



**2. What is a zombie process?**
process that has already finished execution but still not terminated
**3. How does a zombie process get created? How does one get destroyed?**

it gets created by improper execution order. 
they are desktroyed bia waiting on the child process to terminated


**4. What are some of the benefits of working in a compiled language versus a non-compiled language? More specifically, what benefits are there to be had from taking the extra time to compile our code?**

generally compilled code runs faster than interpreted code.
