BASICS

#0 pwd :  prints the absolute path name of the current working directory. 

#1 ls : List the contents of your current directory.

#2 cd ~ (or cd) : that changes the working directory to the user’s home directory.

#3 ls -l : Display current directory contents in a long format.

#4 ls -la : Display current directory contents, including hidden files (starting with .). Use the long format.

#5 ls -lan (or ls -l -a -n) : Display current directory content in long format with hidden file and user and groups IDs displayed numerically.

#6 mkdir /tmp/my_first_directory : that creates a directory named my_first_directory in the /tmp/ directory.

#7 mv /tmp/betty /tmp/my_first_directory : Move the file betty from /tmp/ to /tmp/my_first_directory.

#8 rm /tmp/my_first_directory/betty : delete the file betty in /tmp/my_first_directory.

#9 rmdir /tmp/my_first_directory : Delete the directory my_first_directory that is in the /tmp directory.

#10 cd - : that changes the working directory to the previous one.

#11 ls -la . .. /boot : that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

#12 cat /tmp/iamafile : that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

#13 ln -s /bin/ls  __ls__ : Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory (-s is for make symbolic links).

#14 cp -u *.html .. : Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

#15 mv [[:upper:]]* /tmp/u : Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.

#16 rm *~ : that deletes all files in the current working directory that end with the character ~.

#17 mkdir -p welcome/to/school : that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory (-p is for parent directory).
