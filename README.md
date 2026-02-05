#Linux internal Lab

Mini project 01: Linux privilege Discovery & System call odservation

Description:
This mini project documents my first hand on exploration of Linux from a security perspective.
I set up an Ubuntu Virtual machine and  performed basic system reconnaissance,focusing on:
- Discovering files with special permissions (SUID binaries)
- Understanding how user-level commands interact with the Linux kernel
- Observing real system call using tracing tools.
  
The goal of this project wasn't exploitation, but building Foundatinal intuition about how attackers enumerate systems and how programs actually execute under the hood.

 Key concepts explored:
 - Linux file permissions and SUID behavior
 - Filesystem enumeration using core Linux commands
 - System call (open,read ,write) and kernel interation
 - Why misconfiguration at this level matter for privilege escalation.

This project is part of  my structured cybersecurity learning, focused on learning systems deeply before moving into exploitation and defense.  
