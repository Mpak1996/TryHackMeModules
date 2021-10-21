# Linux Fundamentals 3

![Capture](https://user-images.githubusercontent.com/51766689/134958150-272c7557-dad6-426c-84fa-6b2e1c6a84ab.PNG)

## Task 1 Introduction

   **No Question Needed - Let's start!**

## Task 2 Deploy Your Linux Machine 

**No Question Needed - Let's start!**

   Hint: **ssh username@machineIP**

## Task 3 Terminal Text Editors

* Create a file using Nano

    **No Question Needed - Let's start!**

* Edit "task3" located in "tryhackme"'s home directory using Nano. What is the flag?

    Answer: **THM{TEXT_EDITORS}**

    Command: **nano task3**


## Task 4 General/Useful Utilities

* Download the file http://10.10.43.107:8000/.flag.txt onto the TryHackMe AttackBox. What are the contents?

    Answer: **THM{WGET_WEBSERVER}**

    Command: **python3 -m http.server** -> **wget http://10.10.43.107:8000/.flag.txt** -> **ls -a** -> **cat .flag.txt**

## Task 5 Processes 101

* If we were to launch a process where the previous ID was "300", what would the ID of this new process be?

    Answer: **301**

* If we wanted to cleanly kill a process, what signal would we send it?

    Answer: **SIGTERM**

* Locate the process that is running on the deployed instance (10.10.43.107). What flag is given?

    Answer: **THM{PROCESSES}**

* What command would we use to stop the service "myservice"?

    Answer: **systemctl stop myservice**

* What command would we use to start the same service on the boot-up of the system?

    Answer: **systemctl enable myservice**

* What command would we use to bring a previously backgrounded process back to the foreground?

    Answer: **fg**

## Task 6 Maintaining Your System: Automatation

* Ensure you are connected to the deployed instance and look at the running crontabs.

    Command: **crontab -e**

* When will the crontab on the deployed instance (10.10.5.251) run?

    Answer: **@reboot**

    Command: **crontab -e**

## Task 7 Maintaining Your System: Package Management

   **Not question needed**

## Task 8 Maintaining Your System: Logs

* What is the IP address of the user who visited the site?

    Answer: **10.9.232.111**

    Command: **cd /var/log** -> **cd apache2** -> **nano access.log.1**

* What file did they access?

    Answer: **catsanddogs.jpg**

    Command: **cd /var/log** -> **cd apache2** -> **nano access.log.1**

## Task 9 Conclusions and Summaries

   **Not question needed**

