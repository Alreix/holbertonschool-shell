PERMISSIONS

#0 su [username] : Change the current user.

#1 whoami : print the effective username of the current user.

#2 groups [user] : prints all the groups the current user is part of.

#3 chown [user] [file] : Change the owner of a file to a particular user. 

#4 touch [file] : create an empty files.

#5 chmod u+x [file] : adds execute permission to the owner of the file.

#6 chmod ug+x,o+r [file] : adds execute permission to the owner and the group owner, and read permission to the other users.

#7 chmod ugo+x [file] : adds execution permission to the owner, the groups and other users.

#8 chmod 007 [file] : remove permission to user and groups and add all permissions to other users.

#9 chmod 753 [file] : set the mode of file like this -rwxr-x-wx (all permission for the user, read and excute permission for the groups, write and execute for other users)

#10 chmod --reference=[file reference] [file] : set the mode of a file similar to an other file despite changes. 

#11 chmod -R a+x . : adds exectute permissions to all of the current directory.

#12 mkdir --mode=751 [name of directory] : create a directory with permissions 751 in the working directory.

#13 chown :[group] [file] OR chgrp [group] [file] : change the group owner for a file.

#14 chown -R [user]:[group] . : changes the owner and the group for all files and directory in the current directory.

#15 chown -h [user]:[group] [file] : change the owner and group owner with a symbolic links.

#16 chown --from=[base user] [new user] [file] : changes the owner of one file only if the owner is different. 
