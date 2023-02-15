Write a script that prints the absolute path name of the current working directory- echo $(pwd)
Display the contents list of your current directory- ls -1
Write a script that changes the working directory to the user’s home directory- cd ~
Display current directory contents in a long format- ls -l
Display current directory contents, including hidden files (starting with .). Use the long format- ls -al
Display current directory contents (Long format)(with user and group IDs displayed numerically)(And hidden files (starting with.)- ls -aln
Create a script that creates a directory named my_first_directory in the /tmp/ directory- mkdir /tmp/my_first_directory
Move the file betty from /tmp/ to /tmp/my_first_directory- mv /tmp/betty /tmp/my_first_directory
Delete the file betty- rm /tmp/my_first_directory/betty
Delete the directory my_first_directory that is in the /tmp directory- rm -r /tmp/my_first_directory
Write a script that changes the working directory to the previous one- cd -
Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format- ls -al . .. /boot
Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script- file /tmp/iamafile
Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory- ln -s /bin/ls __ls__
Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.You can consider that all HTML files have the extension .html- cp -rua *.html ../
Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u- mv [[:upper:]]* /tmp/u
Create a script that deletes all files in the current working directory that end with the character ~- rm *~
Create a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory. You are only allowed to use two spaces (and lines) in your script, not more- mkdir -p welcome/to/school
Write a command that lists all the files and directories of the current directory, separated by commas (,). A. Directory names should end with a slash (/) B. Files and directories starting with a dot (.) should be liste C. The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning D. Only digits and letters are used to sort; Digits should come first E. You can assume that all the files we will test with will have at least one letter or one digit F. The listing should end with a new line- ls -map
 
