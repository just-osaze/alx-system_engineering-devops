#!/bin/bash
0. Write a script that prints “Hello, World”, followed by a new line to the standard output (echo -e "Hello, World\n")
1. Script that displays a confused smiley (echo "\"(Ôo)'")
2. Display the content of the /etc/passwd file (less /etc/passwd)
3. Display the content of /etc/passwd and /etc/hosts (cat /etc/passwd && cat /etc/host)
4. Display the last 10 lines of /etc/passwd (tail -10 /etc/passwd)
5. Display the first 10 lines of /etc/passwd6. (head -10 /etc/passwd)
6. A script that displays the third line of the file iacta (cat iacta | head -3 | tail -1)
7.
8. A script that writes into the file ls_cwd_content the result of the command ls -la (ls la > ls_cwd_content)
9. A script that duplicates the last line of the file iacta (tail -n 1 iacta >> iacta)
10. A script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders. (rm *.js)
11. A script that counts the number of directories and sub-directories in the current directory. (find . -mindepth 1 -type d | wc -l)
12. A script that displays the 10 newest files in the current directory. 
13. Being unique is better than being perfect (sort | uniq -u)
14. Display lines containing the pattern “root” from the file /etc/passwd (grep "root" /etc/passwd)
15. Display the number of lines that contain the pattern “bin” in the file /etc/passwd (grep -c "bin" /etc/passwd)
16. Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd (grep -A 3 "root" /etc/passwd)
17. Display all the lines in the file /etc/passwd that do not contain the pattern “bin” (grep -v "bin" /etc/passwd)
18.
19.
