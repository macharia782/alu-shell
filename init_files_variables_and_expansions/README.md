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
echo {a..z}{a..z} | tr ' ' '\n' | grep -v oo : prints all possible combinations of two letter, except oo.
printf "%.2f\n" $NUM : prints a number with two decimal places, followed by a new line.
tr 'A-Za-z' 'N-ZA-Mn-za-m' : encodes and decodes text using the rot13 encryption
paste - - | cut -f1 : prints every other line from the input, starting with the first line.
echo $(printf '%o\n' $(( $(echo $WATER | tr 'water' '01234') + $(echo $STIR | tr 'stir.' '01234') )) | tr '01234567' 'bestchol'): adds the two numbers stored in the environment variables WATER and STIR and prints the result.
