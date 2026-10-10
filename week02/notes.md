1. The pwd printed the path of directory that I'm currently working in.
2. the command ls -a shows hidden files and folders starting with (.) , which plain ls doesn't show.
3. if you use the command ls -l then you will get the complete information of file like data ,time, size, file type,etc. The first column gives the file type like d or - repesenting directory or file in a folder.
4. it is a relative path as it does not start from beggining/ root. Since coding cafe folder is directly inside the current working directory the sytem can find and follow the path dow to week02 and give the files inside week02 using command ls without even opening the coding cafe directory using (cd coding-cafe).
5. mv did two jobs. First it moved the new created file to week01/ directory and then second time it  changed the name of file from README-backup.md to old-readme.md within the directory week01.
There are 20 folders in my PATH.
7. My python3 path is (or) where it lives is: /usr/bin/python3.
8. Both are same.
9. the shell said "Command 'pyton3' not found" and also suggests me to install sudo apt. This error means that the shell searced all folder in my system's PATH but wasn't able to find any exutable program named pyton3. Due to the typo, the command doesn't exist in system's PATH resulting in an error.
10. the .venv appeared when I used ls -a but didn't appear when I used plain ls because when I created virtual environment with my computer it ended up creating hidden file in directory i'm using which is only showed by the command ls -a .
11. My computer shows .venv before path indivating that i'm working in virtual environment now.
12. psth here is different. here python3 is stored in a virrtual environment in my coding-cafe folder instead in my user in my computer .
13. In the second list, it added new packages named "certifi", "charset-normaliser", "idna", "requests" and "urllib3", which were not in the first one. the first one had only "pip", which the second one also has.
14. python3 is back to where it was in step 7, indicating that I have come out of the virtual environment.
15. ls -h prints only "human readable files". A quick google search says that human readable files are those that are stored in text, which a human can read and understand.
16. ctrl c just made python throw a "keyboardinterrupt" error, indicating that i interrupted an input. ctrl d, on the other hand, made the python3 terminal quit entirely.

