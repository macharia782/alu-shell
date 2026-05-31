su betty : this command switches the current user to the user betty.
whoami : this command prints the username of the current user.
groups : this command prints all the groups the current user is part of.
chown betty hello : this command changes the owner of the file hello to the user betty.
touch hello : this command creates an empty file called hello.
chmod u+x hello : this command adds execute permission to the owner of the file hello.
chmod ug+x+r hello : this command adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod a+x hello : adds execution permission to the owner, the group owner and the other users, to the file hello.
chmod 007 hello : this commands gives all permissions to others only and none for owner and group.
chmod 753 hello : this command gives the file owner full read, write, and execute permissions (7), the group read and execute permissions (5), and all other users write and execute permissions (3)
chmod --reference=olleh hello : copies the exact file permissions of olleh and applies them to hello.
chmod a+x */ : adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users leaving regular files unchanged. 
