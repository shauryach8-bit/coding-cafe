    1) Where am I?
1) pwd printed the present working directory or the current location/folder in which we are working.
2) ls - a showed all the files including all the hidden ones which was not shown by only ls.
3) ls -l showed the long detailed form of all files, with information about each file rather than its content. The first column (like drwxr-xr-x) shows the file type (d means directory, - means file) and the read/write/execute permissions for the owner, the group and everyone else.
    2) Build the folder
4) That works because it gave the computer a relative path to go to and it jumped there. coding-cafe/week02 is a relative path because it tells the shell where to go relative to the current working directory.
    3) Move,copy,rename,delete
5) The first job mv did was move README-backup.md into the week01 folder. The second job was rename it from README-backup.md to old-readme.md, so mv both moves and renames files.
    4) Where does the shell find things?
6) there are 10 folders in my user/home path.
7) /usr/bin/python3
8) The person next to me has Python installed/configured in a different location on their computer, so their shell finds a different Python executable.
9) The shell searches the directories listed in your PATH for an executable called python3. Because of my typo, none of those directories contains a program called pyton3, so the shell said pyton3: command not found.
    5) A box of your own
10) .venv does not appear with plan ls simply because plain ls does not show files that begin with a dot. on the other hand ls-a has the capability to show files that begin with a dot because it shows all the files.
11) (.venv) appeared at the start of my prompt. It shows that the virtual environment is active.
12) No, it is not the same path. It now points to ~/coding-cafe/.venv/bin/python3 instead of /usr/bin/python3. This shows that activate put the .venv/bin folder at the front of my PATH, so the shell finds the venv's Python first.
13) In the second 'pip list', pip downloaded some extra modules pertaning to the module requests that got added.
14) back to the same directory as from question 7
15) ls -h shows file sizes in a human-readable way, like 4.0K or 2.1M instead of a long number of bytes. It only makes a difference together with -l (ls -lh), because plain ls does not show sizes.
16) Ctrl + c just made a new line in the terminal for the next command to enter whereas ctrl + d made the terminal exit the python workspace back to the terminal command line. 