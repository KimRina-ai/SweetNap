# SweetNap
C program to help her longest nap with the task

***Input***
-The first line of each case contains integer s<100, representing the number of scheduled appointments for that day.
-The next s lines contain the appointments in the format time1 time2 appointment, where time1 represents the time which the appointment starts and time2 the time it ends.
-The time slot will be in the hh:mm format; the ending time will always be strictly after the starting time and separated by a single space.
-All times will be greater than or equal of 10:00 and less than or equal to 18:00. Thus, your response must be in this time interval.
-The appointment can be any sequence of characters but will always be on the same single line.
-You can assume that no line is longer than 255 characters, that 10<hh<18 and that 00<mm<60
-You cannot assume, however, that the input will be in any specific order, and must read the input until you reach the end of file.

***Output***
-For each test case, you must write a file in the following format:
    Line1 : starting time in hh:mm
    Line2 : duration in hh:mm
-That represents the longest nap starts at hh:mm and will last for hh hours and mm minutes.
-If there is more than one longest nap with the same duration, print the earliest one.
