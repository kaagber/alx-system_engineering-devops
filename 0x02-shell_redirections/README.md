Task 0. Write a script that prints “Hello, World”, followed by a new line to the standard output.

Task 1. Write a script that displays a confused smiley "(Ôo)'.

Task 2. Display the content of the /etc/passwd file.

Task 3. Display the content of /etc/passwd and /etc/hosts

Task 4. Display the last 10 lines of /etc/passwd.

Task 5. Display the first 10 lines of /etc/passwd.

Task 6. Write a script that displays the third line of the file ‘iacta’. The file ‘iacta’ will be in the working directory. You’re not allowed to use ‘sed’.

Task 7. Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

Task 8. Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

Task 9. Write a script that duplicates the last line of the file ‘iacta’. The file ‘iacta’ will be in the working directory.

Task 10. Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

Task 11. Write a script that counts the number of directories and sub-directories in the current directory. Make sure:
a. The current and parent directories should not be taken into account
b. Hidden directories should be counted

Task 12. Create a script that displays the 10 newest files in the current directory. Requirements:
a. One file per line
b. Sorted from the newest to the oldest

Task 13. Create a script that takes a list of words as input and prints only words that appear exactly once. Requirements:
a. Input format: One line, one word
b. Output format: One line, one word
c. Words should be sorted

Task 14. Display lines containing the pattern “root” from the file /etc/passwd.

Task 15. Display the number of lines that contain the pattern “bin” in the file /etc/passwd.

Task 16. Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

Task 17. Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

Task 18. Display all lines of the file /etc/ssh/sshd_config starting with a letter. Include capital letters as well.

Task 19. Replace all characters A and c from input to Z and e respectively.

Task 20. Create a script that removes all letters c and C from input.

Task 21. Write a script that reverse its input.

Task 22. Write a script that displays all users and their home directories, sorted by users.

Task 23. Write a command that finds all empty files and directories in the current directory and all sub-directories.
a. Only the names of the files and directories should be displayed (not the entire path).
b. Hidden files should be listed.
c. One file name per line.
d. The listing should end with a new line.
e. You are not allowed to use basename, grep, egrep, fgrep or rgrep.

Task 24. Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories.
a. Hidden files should be listed.
b. Only regular files (not directories) should be listed.
c. The names of the files should be displayed without their extensions.
d. The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay). 
e. One file name per line.
f. The listing should end with a new line.
g. You are not allowed to use basename, grep, egrep, fgrep or rgrep

Task 25. An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval. 
a. Create a script that decodes acrostics that use the first letter of each line.
b. The ‘decoded’ message has to end with a new line. 
c. You are not allowed to use grep, egrep, fgrep or rgrep.

Task 26. Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
Order by number of requests, most active host or IP at the top. 
You are not allowed to use grep, egrep, fgrep or rgrep.
Format:
a. host -   When possible, the hostname making the request. Uses the IP address if the hostname was unavailable;
b. Logname - Unused, always -;
c. Time - In seconds, since 1970;
d. Method - HTTP method: GET, HEAD, or POST;
e. url - Requested path;
f. response - HTTP response code;
g. Bytes - Number of bytes in the reply;
