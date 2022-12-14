---
l1Cat: "Coursework"
l2Cat: "Unit 1"
l3Cat: "Section 03 - More algorithms and math"
title: "1AB - Building an alogirhtm"
layout: "../../../../layouts/Coursework.astro"
---

# Assignment: DIY sorting algorithm

In this assingment, you will be developing a custom sorting algorithm. The goal of this project is to devise and implement the most efficient possible algorithm that can sort a list of integers. This program is broken into two parts: algorithm design, and implementation. The design segment will be worth 1/2 of your grade, and the other half will be your implementation of your code.

## Part 0: Algorithm design
Before implementing an algorithm, you must plan out what you are going to build, and then create a flowchart descriibng your algorithhm. (AP requires at least one flowchart assignment) You will be given an randomly long array of integers, and your program must produce a sorted version of this array. Your flowchart should model the core sorting function of your program, but you do not need to model the I/O or glue logic in your chart. You can either use [Draw.IO](draw.io), or draw your flowchart on paper. Please submit this flowchart into the assignment labeled 1A in Canvas.  
  
This section will be graded based on the quality of your flowchart and the theoretical workability of your algorithm. The proformance of your algorithm will be graded seperatley.

## Part 1: Implementation
You will now implement your algorithm as a python program. Your program should start by accepting on line of input, containing an integer, *n*, which indicates the number of times your program is going to run. After this, your program should accept *n* lines of input, each of which contains an unordered list of integers. Each integer will be seperated by a space. (Use the ntr header and string splitting examples if you need help with this) Your program should then print the final sorted list. Your program should also include a try/except block to catch errors in your program. (A general error handler is good here, you do not need to handle a spesific type of exception) This block should be able to detect when a user inputs a string instead of a series of numbers. Think about where this kind of error may appear.  Please submit this part of the assingment using the turnin command on the server. (`turnin 1B@apcsp main.py`) Before turning your work in, please ensure that your program:
- Follows the input spesifications
- Prints a sorted list
- Is contained in a main.py file
- Includes comments and scoping (functions, etc)
- Contains a try/except block

## Grading and efficiency
When grading for efficiency, several trials will be run against your program, and I will use your average to determine efficiency. I am not looking for perfect proformance, and I really just want to see that you have made something that works, and that you have made a creative attempt at the problem. I would much prefer that you take the time to build something simple and original as opposed to copying something. **I also want you to ensure that your program takes input correctly. The code for these functions is on the website. I will not mark programs that do not follow the input spesifications.** 
