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
