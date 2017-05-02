0-current_working_directory
prints the absolute path name of the present working directory

1-listit
displays the contents of present working directory

2-bring_me_home
changes present working directory to user's home directory (bug: shebang generates a sub-shell, such that its home directory is not observed, and user's home directory is not reached)

3-listfiles
displays present working directory's contents in long format

4-listmorefiles
displays present working directory's contents, including hidden files, in long format

5-listfilesdigitonly
displays present working directory's contents, with user and group IDs displayed numerically, including hidden files, in long format

6-firstdirectory
creates a directory named "holberton" in /tmp/ directory

7-movethatfile
moves file "betty" from /tmp/ directory to /tmp/holberton/ directory

8-firstdelete
deletes file "betty" from /tmp/holberton/ directory

9-firstdirdeletion
deletes directory /holberton/ from /tmp/ directory

10-back
changes present working directory to previous working directory

11-lists
lists all files, including hidden files, in present working directory, its parent directory, and /boot/ directory, in that order, in long format

12-file_type
prints type of file, for file "iamafile", which is found in /tmp/ directory

13-symbolic_link
creates symbolic link to /bin/ls, named _ls_, within present working directory

14-copy_html
copies all HTML files from present working directory into its parent directory, ONLY IF those files are NOT present or OLDER versions in parent directory

15-lets_move
moves all files that begin with uppercase letter into /tmp/u/ directory, if it exists

16-clean_emacs
deletes all files from present working directory that end with ~ (these are emacs' autosaved files)

17-tree
creates the directory /welcome/, with subdirectory /to/, which has its own subdirectory /holberton/, within present working directory

18-commas
lists all files and directories in present working directory, including hidden files and directories, with formatting: directories "." and ".." are listed first, followed by files and directories which begin with a digit (presented in numerical order), followed by files and directories which begin with a letter (presented in alphabetical order)
