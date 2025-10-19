INIT FILES VARIABLES AND EXPANSIONS

#0 alias ls="rm -f *" : create an alias with ls and rm.

#1 echo "hello $USER" : print hello user where user is the current Linux user.

#2 PATH=$PATH:/action : add /action to the PATH. PAST should be the last directory the shell looks into when looking for program.

#3 echo $PATH | tr ':' '\n' | grep / | wc -l : counts the number of directories in the PATH.

#4 printenv : list environment variable

#5 set : lists all local variable and environment variable and functions. 

#6 BEST=School : create a local variable.

#7 export BEST=School : create a global variable.

#8 echo $((128 + 1209)) : prints the result of addition of 128 et 1209.

#9 echo $(($POWER/$DIVIDE)) : prints the result of POWER divided by DIVIDE, followed by new line.

#10 echo $(($BREATH**$lOVE)) : displays the result of BREATH to the power LOVE.

#11 echo $((2#$BINARY)) : that convert a number from base 2 to base 10.

#12 echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo" : prints all possible combinations of two letters, except oo. (letter are lower case from a to z).

#13 printf "%.2f\n" "$NUM" : prints a number with two decimal places, followed by a new line.

#14 printf "%x\n" "$DECIMAL" : converts a number from base 10 to base 16.

#15 tr 'A-Za-z' 'N-ZA-Mn-za-m' : that encodes and decodes text using the rot13 encryption. Assume ASCII.

#16 paste - - | cut -f1 : that prints every other line from the input, starting with the first line.

#17 printf "%o\n" $(( 5#$(echo $WATER | tr 'water' '01234') + 5#$(echo $STIR | tr 'stir.' '01234'))) | tr '01234567' 'bestchol'


