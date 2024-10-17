Task 0 : Create a script that creates an alias.
    Name: ls
    Value: rm *
       alias Is='rm *' instead of alias ls = "rm *"  and no spacing between Is='rm 

Task 1 : Create a script that prints hello user, where user is the current Linux user.
          echo "hello " $USER instead of  echo hello $USER , alias user="whoami" | echo "hello "user

Task 2 : Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
           PATH=$PATH:/action instead of PATH=$PATH:./action

Task 3 : Create a script that counts the number of directories in the PATH
	echo $PATH | tr -s ":" "\n" | wc -l  instead of  echo $PATH | tr ":" "\n" | wc -l , PATH | tr ":" "\n" | wc -l instead of    echo $PATH | wc -l 

Task 4 : Create a script that lists environment variables.
	printenv 

Task 5 : Create a script that lists all local variables and environment variables, and functions.
	set

Task 6 : Create a script that creates a new local variable.
    Name: BEST
    Value: School
 answer ->	BEST="School"

Task 7 : Create a script that creates a new global variable.
    Name: BEST
    Value: School
answer ->	export BEST="School"

Task 8 : Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
	echo $((TRUEKNOWLEDGE=TRUEKNOWLEDGE+128))      or echo $((($TRUEKNOWLEDGE)+128))

Task 9 : Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.
    POWER and DIVIDE are environment variables
answer -> echo  $((POWER/DIVIDE))

Task 10 : Write a script that displays the result of BREATH to the power LOVE

    BREATH and LOVE are environment variables
    The script should display the result, followed by a new line
Answer -> echo $((BREATH**LOVE))      not printf $((BREATH**LOVE))    -> why ???
Not   printf $((pow(BREATH,LOVE)) Not	printf $((BREATH^LOVE))

Task 11 : Write a script that converts a number from base 2 to base 10.
    The number in base 2 is stored in the environment variable BINARY
    The script should display the number in base 10, followed by a new line
Answer -> echo $((2#$BINARY))

NOT  echo $((2#($BINARY))) 	
         
not printf "%d\n, $BINARY not printf "%d\n","$ ((2#$BINARY))" These two works on command line 

Task 12 : Create a script that prints all possible combinations of two letters, except oo.

    Letters are lower cases, from a to z
    One combination per line
    The output should be alpha ordered, starting with aa
    Do not print oo
    Your script file should contain maximum 64 characters

Answer - > echo {a..z}{a..z} | tr " " "\n" | grep -v "oo"

not echo {a..z}{a..z} | tr " " "\n" | tr -d "oo"
not  echo {a..z}{a..z} , o {a..z}{a..z} | tr -d "oo" | tr " " "\n" | grep


