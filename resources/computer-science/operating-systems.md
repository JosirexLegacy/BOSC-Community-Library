\# Operating Systems — What's Actually Happening Under the Hood



Most students treat the OS as background noise. That's a mistake.

Understanding how an operating system works helps you write better code,

debug harder problems, and understand why your program behaves the way it does.



\---



\## Key Topics You Should Understand



\*\*1. Processes and Threads\*\*

A process is a running program. A thread is a unit of work inside that process.

Your browser right now is one process running dozens of threads simultaneously.



\*\*2. Memory Management\*\*

How does your computer decide where to store data?

How does it handle more programs than it has RAM for?

This is where concepts like paging, virtual memory, and segmentation come in.



\*\*3. File Systems\*\*

How files are actually stored on disk — not just folders and names,

but inodes, blocks, and how deletion really works.



\*\*4. Scheduling\*\*

When 10 programs want the CPU at once, the OS decides who goes first.

Understanding scheduling helps you reason about performance.



\*\*5. Deadlocks\*\*

When two processes each wait for the other to finish — forever.

Classic exam topic and a real problem in production software.



\---



\## Free Learning Resources



\- \*\*OS: Three Easy Pieces (Free PDF)\*\* — https://pages.cs.wisc.edu/\~remzi/OSTEP/

&#x20; Written by university professors. Free, downloadable, readable offline.

&#x20; Probably the best free OS textbook that exists.



\- \*\*Neso Academy (YouTube)\*\* — https://www.youtube.com/c/NesoAcademy

&#x20; Short, clear videos on every OS topic. Good for exam prep.



\- \*\*GeeksforGeeks OS Section\*\* — https://www.geeksforgeeks.org/operating-systems/

&#x20; Quick reference for definitions and diagrams.



\---



\## Practical Tip



If you use Linux (or even WSL on Windows), you already have a live OS to

experiment with. Try commands like `top`, `ps`, `df`, and `free` to see

OS concepts running in real time.



\---



\*Contributed by the BOSC Community. Last reviewed: 2025.\*

