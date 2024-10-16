 prints Hello, World, followed by a new line to the standard output ( echo "Hello World\n" )
 Display confusing smiley  "(Ôo)'( echo \""(Ôo)"
Display the content of the /etc/passwd file ( cat /etc/passwd )
Display the content of /etc/passwd and /etc/hosts ( cat /etc/passwd /etc/hosts )
Display the last 10 lines of /etc/passwd ( tail -n10 /etc/passwd )
Display the first 10 lines of etc/passwd ( head -n10 /etc/passwd )
Write a script that displays the third line of the file iacta ( head -n 3 iacta | tail -n 1 instead of awk 'NR==5{ print; exit }' README.md )
creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line. (
 echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)   instead of    echo -e "Best School\n" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)  ,     echo -e "Best School\n" > \\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)  )

writes into the file ls_cwd_content the result of the command ls -la ( ls -la > ls_cwd_content )
duplicates the last line of the file iacta ( tail -n 1 iacta >> iacta )
deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders ( 
  find . -type f -name "*.js" -delete
  instead of find -name "*.js" -exec /bin/rm {} \; 
  instead of  find . -name "*.js" -exec /bin/rm -i {} \;
  instead of   rm ./*.js | rm ./*.*/*.js )
counts the number of directories and sub-directories in the current directory ( find . -type d -not -name "." |wc -l  instead of find . -type d | wc -l) 
displays the 10 newest files in the current directory ( ls -t | head -n 10 )
a list of words as input and prints only words that appear exactly once ( ls -l | uniq -u )


