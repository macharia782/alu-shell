alias ls="rm *" : Creates an alias
echo "hello $USER" : Prints hello user where the user is the current Linux user.
export PATH=$PATH:/action : Adds /action to the PATH and is the last program when search is looking.
echo "$PATH" | tr ':' '\n' | grep -v '^$' | wc -l : counts the number of directories in the PATH.
printenv : this command lists environment variables.
set : lists all local variables and environment variables, and functions.
BEST=School : Creates a local variable with the value School.
export BEST=School : Creates a new global variable.
