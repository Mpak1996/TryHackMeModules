# Linux Fundamentals 1

![Capture](https://user-images.githubusercontent.com/51766689/134958150-272c7557-dad6-426c-84fa-6b2e1c6a84ab.PNG)

## Task 1 Introduction

**No Question Needed - Let's start!**

## Task 2 A Bit of Background on Linux

* Research: What year was the first release of a Linux operating system?

    Answer: **1991**

## Task 3 Interacting With Your First Linux Machine (In-Browser)

**I've deployed my first Linux machine!**

## Task 4 Running Your First few Commands

* If we wanted to output the text "TryHackMe", what would our command be?

    Answer: **echo TryHackMe**

* What is the username of who you're logged in as on your deployed Linux machine?

    Answer: **TryHackMe** 
    
    Using Command: **whoami** 

## Task 5 Interacting With the Filesystem!

![task5](https://user-images.githubusercontent.com/51766689/135131232-6f58065c-f8da-41a5-8ff4-9c571460d754.PNG)

* On the Linux machine that you deploy, how many folders are there?

    Answer: **4** 
    
    Using Command:**ls**

* Which directory contains a file? 

    Answer: **folder4** 
    
    Using Command: **cd folder4**

* What is the contents of this file?

    Answer: **Hello World** 
    
    Using Command: **cat note.txt**

* Use the cd command to navigate to this file and find out the new current working directory. What is the path?

    Answer: **/home/tryhackme/folder4**
    
    Using Command:**pwd**


## Task 6 Searching for Files

![UsingFind](https://user-images.githubusercontent.com/51766689/135303938-55e90637-d420-438b-9cb8-49ede756e9fb.PNG)

![UsingGrep](https://user-images.githubusercontent.com/51766689/135303934-c63ad10b-e942-478d-8b2e-77f9bab528e8.PNG)

* Use grep on "access.log" to find the flag that has a prefix of "THM". What is the flag?

 Answer: **THM{ACCESS}** 
 
 Using Command: **grep "THM" access.log**

## Task 7 An Introduction to Shell Operators

## Task 8 Conclusions & Summaries

## Task 9 Linux Fundamentals Part 2