Unix commands
----------------
**Part 1**

1. pwd  - returns present working directory
2. cd ~/  - returns to home directory
3. ls -al   - lists all files with attributes in vertical format
4. echo hello world  -send text to screen
5. date - returns day of week, date, time, timezone
6. hostname  - returns computer name
7. arch - returns computer architecture type
8. uname -a  - prints the name, version and other details about the current machine and the operating system running on it
9. uptime - gives how long system has been running
10. whoami - returns username
11. id - shows your User ID (UID) and Group ID (GID) [as set in /etc/passwd], as well as all of the groups you are in
12. last - lists recent logins
13. ps aux - show process info for all users
14. top - displays a listing of the most CPU-intensive tasks on the system, and can provide an interactive interface for manipulating processes.
15. man “automatic door”  - displays online manuals for “automatic door”
16. man who - displays online manual for who command
17. man top  -  displays online manual for top command
18. clear - clears screen
19. cal 2000 - displays calendar for year 2000
20. cal 9 1752 - displays calendar for September 1752
21. yes please - outputs please continuously unless interrupted by user
22. time sleep 3 - reports how long it takes for the command sleep 3 to execute
23. ping lighthouselabs.ca - is used to test whether lighthouselabs.ca is reachable over a network
24. history - lists previously typed commands

**Part 2**
<br>
1. cat /usr/share/dict/words - displays file contents of words
2. cat /usr/share/dict/words | grep "ous$" - lists all words in words file containing ous
3. wc -l /usr/share/dict/words - returns number of entries or lines  in words file.
4. cat /usr/share/dict/words | grep "ous$" | wc -l - displays the number of words containing ous in words file
5. ls -al /usr/share > ~/ls.txt - list all files under usr/share/ directory and outputs this list into text file ls in the home directory
6. less ~/ls.txt  - view file contents of ls.txt
7. nano ~/ls.txt - opens ls.txt in nano editor
