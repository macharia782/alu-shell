alias ls="rm *" : Creates an alias
echo "hello $USER" : Prints hello user where the user is the current Linux user.
export PATH=$PATH:/action : Adds /action to the PATH and is the last program when search is looking.
echo "$PATH" | tr ':' '\n' | grep -v '^$' | wc -l : counts the number of directories in the PATH.
printenv : this command lists environment variables.
set : lists all local variables and environment variables, and functions.
BEST=School : Creates a local variable with the value School.
export BEST=School : Creates a new global variable.
echo $((128+$TRUEKNOWLEDGE)) : Prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
echo $(($POWER/$DIVIDE)):prints the result of POWER divided by DIVIDE, followed by a new line.echo
echo $(($BREATH**$LOVE)) :  displays the result of BREATH to the power LOVE
echo $((2#$BINARY)) : converts a number from base 2 to base 10
