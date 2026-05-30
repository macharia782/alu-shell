The pwd command prints the absolute path of the current working directory.
The ls command lists the contents of the current directory.
cd ~ : This is a command one can use to change the working directory to the user's home directory.
ls -l : This command displays current directory contents in a long format.
ls -la : This command dispays all files in the current directory including the hidden files.
ls -lan : This  command Display current directory contents in long format with user and group IDs displayed numerically, and hidden files.
mkdir /tmp/my_first_directory : This creates a directory named my_first_directory in the /tmp/ directory.
mv /tmp/betty /tmp/my_first_directory : Moves  the file betty from /tmp/ to /tmp/my_first_directory.
rm /tmp/my_first_directory/betty : Deletes the file betty in the directory.
rm -rf /tmp/my_first_directory : Deletes the directory my_first_directory that is in the /tmp directory
cd - : Changes the directory to the previous one.
ls -la . .. /boot : all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile : prints the type of the file named iamafile.
ln -s /bin/ls __ls__ : creates a symbolic link in the curent working directory to /bin/ls, named __ls__
cp -u *.html ../ : copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
mv [A-Z]* /tmp/u :  moves all files beginning with an uppercase letter to the directory /tmp/u.
