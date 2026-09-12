# Level 4
## Task:
The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.
## Solution:

The command file ./-* determines the file type of all files in your current directory whose names start with a dash (-).
* file: Inspects the contents of a file and prints its type (e.g., ASCII text, binary data, gzip compressed).
* ./: Explicitly specifies the current working directory path.
* -*: Matches any file name that begins with a dash or hyphen.
* The ./ prefix prevents the command from misinterpreting a filename starting with - (such as -testfile) as a command-line option or flag.

Used 'file ./-*' command. It listed the files in the directory and their types. 
-file07 was the only with text.
'cat ./-file07'
Password was: 6C7h9GD8M6ai5nr7wo1RonrzFjj9yIrG
