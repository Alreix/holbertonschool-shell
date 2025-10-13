REDIRECTION AND FILTERS

#0 echo "Hello, Wolrd" : prints "Hello, World" followed by a new line to the standart output.

#1 echo "/"(Ôo)'" : display a confused smiley.

#2 cat [file] : display the content of file in stdout directly.

#3 cat [file1] [file2] : display the content of file1 and file2 directly on stdout.

#4 tail -n 10 [file] : display the last 10 lines of the file.

#5 head -n 10 [file] : display the 10 first line of a file.

#6 head -n 3 [file] | tail -n 1 : display the third line of file even if the content of the file change.

#7 echo "Best School" > \\\*\\\\\'\"Best\ School\"\\\'\\\\\*$\\\?\\\*\\\*\\\*\\\*\\\*:\) : create a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) and containing the text Best School.

#8 ls -la > [file] : write into the file the result of the command ls -la and overwritten if the file exist.

#9 tail -n 1 [file] >> [file] : duplicate the last line of the file in file.

#10 find . -type f -name '*.js' -delete : delete all the regular files (not the directories) with .js extension that are present int the current directory.

#11 find . -mindepth 1 -type d | wc -l : counts the number of directories and sub-directories in the current directory.

#12 ls -t | head -n 10 : displays the 10 newest files int the current directory.

#13 sort | uniq -u : take a list of words as input and prints only words that appear exactly once.

#14 grep root /etc/passwd : display lines containing the pattern "root" form the file /etc/passwd.

#15 grep bin /etc/passwd | wc -l : display the number of lines that contain the pattern 'bin' in /etc/passwd.

#16 grep -A 3 'root' /etc/passwd : display lines containing the pattern "root" and 3 lines after them in the file etc/passwd.

#17 grep -v 'bin' /etc/passwd : display all the lines in the file /etc/passwd that do not contain the pattern "bin".

#18 grep [[:alpha:]]* /etc/ssh/sshd_config : display all line of the file /etc/ssh/sshd_config starting with a letter.

#19 tr 'Ac' 'Ze': replace all characters A et c from input to Z and e respectively.

#20 tr -d 'Cc' : removes all letters c and C from input. 

#21 rev : reverse the input.

#22 cut -d: -f1,6 /etc/passwd | sort : displays all users and their home directories, stored by users.

