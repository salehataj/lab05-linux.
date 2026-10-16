# Security Detective Challenge

## Question 1: Current User and Home Folder
Answer: I am logged in as salehataj. My home folder is /home/salehataj.
Commands: `whoami`, `pwd`

## Question 2: Server Name and Ubuntu Version
Answer: The server name is ubuntu. I still need to verify the Ubuntu version.
Commands: `hostname`, `lsb_release -a`

## Question 3: RAM and Free Disk Space
Answer: The server has 2.5 GiB of total RAM, with 1.8 GiB available. The root filesystem has 11 GB of free disk space.
Commands: `free -h`, `df -h`

## Question 4: Users Who Can Log In with /bin/bash
Answer: The users shown with the /bin/bash shell are root and salehataj.
Command: `grep '/bin/bash' /etc/passwd`

## Question 5: Number of Processes
Answer: The command reported 230 lines, including the header. Therefore, there are 229 processes.
Command: `ps aux | wc -l`

## Question 6: lab5user Creation and Deletion Times
Answer: The first creation was recorded at 2026-10-16 04:35:59 UTC, and the first deletion was recorded at 2026-10-16 04:37:53 UTC. The user was created again at 2026-10-16 04:38:08 UTC and deleted again at 2026-10-16 04:48:28 UTC. The latest recorded deletion was at 2026-10-16 04:48:28 UTC.
Command: `sudo grep lab5user /var/log/auth.log`
