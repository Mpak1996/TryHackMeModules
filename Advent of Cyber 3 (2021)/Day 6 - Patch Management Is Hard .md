# Day 1 - Save the Gifts

![adventTryHackMe](https://user-images.githubusercontent.com/51766689/144512518-c7fe8bdd-197b-4913-aaf9-12d6a2afdce6.PNG)



* Deploy the attached VM and look around. What is the entry point for our web application?

    Answer: **err**
 
* Use the entry point to perform LFI to read the /etc/flag file. What is the flag?

    Answer: **THM{d29e08941cf7fe41df55f1a7da6c4c06}**

* Use the PHP filter technique to read the source code of the index.php. What is the $flag variable's value?

    Answer: **err**

* Now that you read the index.php, there is a login credential PHP file's path. Use the PHP filter technique to read its content. What are the username and password?

    Answer: **THM{791d43d46018a0d89361dbf60d5d9eb8}**

* Use the credentials to login into the web application. Help McSkidy to recover the server's password. What is the password of the flag.thm.aoc server?

    Answer: **THM{552f313b52e3c3dbf5257d8c6db7f6f1}**

* The web application logs all users' requests, and only authorized users can read the log file. Use the LFI to gain RCE via the log file page. What is the hostname of the webserver? The log file location is at ./includes/logs/app_access.log.

    Answer: **lfi-aoc-awesome-59aedca683fff9261263bb084880c965**

