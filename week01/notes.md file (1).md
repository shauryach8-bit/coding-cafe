    1) Where am I?
1) pwd printed the present working directory or the current location/folder in which we are working.
2) ls - a showed all the files including all the hidden ones which was not shown by only ls.
3) ls - l showed the long detailed form of all files inclduing detailed information of the file, not the content but information of the file itself.
    2) Build the folder
4) That works because it gave the computer a relative path to go to and it jumped there. coding-cafe/week02 is a relative path because it tells the shell where to go relative to the current working directory.
    3) Move,copy,rename,delete
5) the first job that mv did was move the readme backup to week01 and the other job that it did was replace the current backup readme with the old readme.
    4) Where does the shell find things?
6) there are 10 folders in my user/home path.
7) /usr/bin/python3
8) The person next to me has Python installed/configured in a different location on their computer, so their shell finds a different Python executable.
9) The shell searches the directories listed in your PATH for an executable called python3. If none of those directories contains it, you get python3: command not found.
    5) A box of your own
10) .venv does not appear with plan ls simply because plain ls does not show files that begin with a dot. on the other hand ls-a has the capability to show files that begin with a dot because it shows all the files.
11) I think this simply setup a python enviroment in that directory so that we can work with python modules in that path? I think that.
12) activate tells your current shell to use that virtual environment's Python and pip by modifying things like PATH.
13) In the second 'pip list', pip downloaded some extra modules pertaning to the module requests that got added.
14) back to the same directory as from question 7
15) ls -h just gives names of the folders in my path, similar to what only ls does.
16) Ctrl + c just made a new line in the terminal for the next command to enter whereas ctrl + d made the terminal exit the python workspace back to the terminal command line. 