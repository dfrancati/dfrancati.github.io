---
layout: archive
title: ""
permalink: /teaching/csap
sitemap: false
author_profile: false
---

# CSaP - Computer Systems and Programming (2025 - 2026)

**Teacher:** Danilo Francati – [francati@di.uniroma1.it](mailto:francati@di.uniroma1.it)

---

## NEWS


<!-- This is the [project](#) for this year (2025). -->

<!-- Send me code and documentation at least three days before the exam’s date. -->

<!-- Contact me (email) should you need any clarifications. -->

<!-- These are the result for the [third midterm](#), and the [proposed grades](#). -->

<!-- Students can just accept them (send me an email) or, to improve them, register for an oral test at one of the next exam sessions.   -->

<!-- **N.B.:** The grades in ORANGE boxes can be confirmed only **after an oral exam**. -->

<!-- --- -->

<!-- **Today, Dec. 16th, was the last session for AA2024-2025.** -->


---

### Class Timetable
- Monday h.08:00/10:00 – Aula Magna (V.le Regina Elena)  
- Tuesday h.13:00/16:00 – Aula Alfa (Via Salaria)  

Lectures will be delivered in presence.

---

## Office Hours

By appointment.

Students can always use email and/or schedule a webmeeting.

---

## CSAP Google Classroom

A group has been created in order to allow communication, sharing of information, etc.  

The name of the Google Classroom is **CSAP** ([link](TODO))  

Students are invited to join it, in order to receive last minute communications and to get access to the folder where code and slides will be posted.

---

## Objectives

The course is mainly focused on system programming for Unix/Linux systems.

The objective is to make students able to understand, write and modify programs interfacing with the Linux operating system and its kernel source code.  
More precisely, we expect the students to acquire knowledge of:

1. the C language and the tools normally used in the development environment (compiler, preprocessor, shell, etc.)  
2. the fundamental functions of the operating system and its main modules (Scheduler, Virtual Memory Manager, Filesystem, ...)  
3. the main system primitives for the creation and synchronization of processes, exchange of messages and information (this is the core of the course)  
4. basic methods for network programming (sockets)  

At the end, the students are provided by operating system and integrate them correctly into the code:  

- choose the most suitable OS components and functions, based on the needs of the application and their execution mode.  
- determine the complexity and how to implement a system application.  
- acquire the methodology for application development, in order to justify and explain the reasons behind the choices.  
- continue learning by examining, in depth, the more advanced components of the operating system.  

---

## Prerequisites

Formal pre-requisites for the course are the same as the prerequisites for enrollment to the Master in Cybersecurity  
(see [requirements](https://cybersecurity.uniroma1.it/admission#requirements)).  

Our MSc takes for granted the subjects and contents covered in the Italian Bachelor's Degree in Computer Science or Computer Engineering.  
Our MSc offers an in-depth technical study aimed at training experts in Cybersecurity. Therefore, a high technological core is essential, regardless of the orientation chosen within your Study Plan.

In practice, you will need (at least):  
- mastery of one (preferably more) programming language(s)  
- understanding of computer architecture and operating system principles  
- understanding of computer network protocols (preferably TCP/IP)  

Each student should have access to a Linux system (a VM is ok), including the compiler, development tools (make, debugger, etc.) and man pages.  
Ubuntu 22.04 (or later) is the recommended platform.  

Working natively on other devices, such as Mac or Windows laptop, while possible, is not recommended due to subtle differences in the compiler suite and OS interface.  

---

## Exam

TODO

<!-- An evaluation will be carried out, during the course, through **3 midterms**: short programs developed by the students in the classroom using their own laptop.  -->

<!-- At the end of the course, the students will be able to accept the result obtained with these tests and verbalize it, perhaps after an oral discussion.   -->

<!-- As an alternative, or if the result of the tests is not considered acceptable, a complete individual project, written in C, could be developed on a topic pertaining the arguments seen during the course.   -->

<!-- Thus, there are two options:   -->
<!-- 1. Pass the midterms (and, eventually, an oral discussion)   -->
<!-- 2. Complete the project (as described in the dedicated section). The project (sources and documentation) must be sent by email a few days (5-7) before the date of the exam.   -->

<!-- Write/contact me for any doubts, information, etc.   -->

---

## Project

The project is an individual work item, which must include appropriate documentation (Use cases, functional and non functional requirements, etc.).  

Each academic year will have a different project.  
As an example, this was the [Project for AA2021-2022](TODO).  

The code and the docs for the project must be sent by email a few days (3-5) before the session where it will be reviewed/discussed.  

The project must constitute an original creation, therefore it is not possible to share parts of the code or copy contents from other sources.  

However, discussions between students, exchanges of ideas, use of mailing lists, chats, and in general everything that helps the student to learn are legitimate and appreciated (in case of doubts regarding which forms of collaboration are considered legitimate or not, it is better to explicitly ask for clarification).  

The project consists of a C language program that satisfies a set of specified requirements, using the library calls that are part of the course program. The use of other calls is generally not accepted. If in doubt, ask the teacher.  

The project code must correctly compile and execute in the required software environment (compiler version, kernel version, clib version).  

### Evaluation criteria
- **Prerequisite**: the code must correctly compile, link and start on Ubuntu 22.04 (or later).  
- **Correctness of the code**: main evaluation element that determines (alone!) the passing of the exam.  
- **Error handling**: it is an integral part of the correctness of the code!  
- **Modularity and readability of the code**: division into functions, comments, function and variable names (sic!), etc.  
- **Quality of documentation**: user manual, software architecture, README file, project report.  

---

## Program

These are the topics that are planned to be covered during the course.  
Of course mileage may vary, depending on time available, etc.  

- Recap of the C programming language: variables, constants, operators, expressions, control instructions, functions, pointers, arrays, structures & unions, preprocessor directives  
<!-- - Programming environment: compiler, make & makefiles, gdb debugger   -->
- Operating system basics (Linux): processes, filesystem, inter-process communication primitives (signals, pipes, semaphores, shared memory)  
- Network programming: sockets, raw sockets, sniffers  

---

## Recommended Readings

- Daniel P. Bovet, Marco Cesati: *Understanding the Linux Kernel*  
- Brian Kernighan, Dennis Ritchie: *The C Programming Language* (2nd Ed.)  
- Richard Stevens: *Advanced Programming in the UNIX Environment*  
- Brian W. Kernighan, Rob Pike: *The Practice of Programming*  
- M. Mitchell, J. Oldham, A. Samuel: *Advanced Linux Programming*  