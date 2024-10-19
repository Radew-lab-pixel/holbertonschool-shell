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
a list of words as input and prints only words that appear exactly once ( sort | uniq -u instead of ls -l | uniq -u )
Display lines containing the pattern “root” from the file /etc/passwd(grep -w "root" /etc/passwd )
Display the number of lines that contain the pattern “bin” in the file /etc/passwd( grep -c "bin" /etc/passwd instead of    grep -w "bin" /etc/passwd | wc -l)
Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd(  grep -A 3 /etc/passwd 
Display all the lines in the file /etc/passwd that do not contain the pattern “bin�] ( grep -v "bin" /etc/passwd  )
Display all lines of the file /etc/ssh/sshd_config starting with a letter including capital letter . ( grep -i "[A-Z]" /etc/ssh/sshd_config ) 
Replace all characters A and c from input to Z and e respectively. ( tr "A" "Z" | tr "c" "e" instead of 0>&1 | tr "A" "Z" | tr "c" "e" )
Create a script that removes all letters c and C from input ( tr -d cC )
Write a script that reverse its input. ( rev )
Write a script that displays all users and their home directories, sorted by users ( cut -f1,6 -d ":" /etc/passwd | sort instead of sort | cut -f1,6 -d ":" /etc/passwd )

Task 23 : Write a command that finds all empty files and directories in the current directory and all sub-directories.

    Only the names of the files and directories should be displayed (not the entire path)
    Hidden files should be listed
    One file name per line
    The listing should end with a new line
    You are not allowed to use basename, grep, egrep, fgrep or rgrep

 Answer  - > find . -empty |rev | cut -d "/" -f1 |rev 

NOT find .* -size 0 | rev | cut -d "/" -f1 | rev

NOT find .* -size 0 
NOT find .* -size 0 | rev | cut -d "/" -f1 | rev | sort -u
NOt ls -alR | cut -s -f3,9 -d " "   
NOT find .* -empty |  tr -s "/" | cut -f3 -d "/"
NOT find .* -empty | uniq -u |  tr -s "/" | cut -f3 -d "/"
NOT find .* -print -empty | uniq -u |  tr -s "/" | cut -f3 -d "/"
 NOT  find *. -empty | uniq -u  
NOT find *. -empty
NOT 		find empty 

Task 24 : Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories.

    Hidden files should be listed
    Only regular files (not directories) should be listed
    The names of the files should be displayed without their extensions
    The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
    One file name per line
    The listing should end with a new line
    You are not allowed to use basename, grep, egrep, fgrep or rgrep


  Answer :  
find . -type f -name "*.gif" | rev | cut -f1 -d "/" | rev | cut -f1 -d "."  |LC_ALL=C sort
 NOTfind . -type f -name "*.gif" | rev | cut -f1 -d "/" | rev | cut -f1 -d "."  |sort --numeric-sort
NOT find .* -type f -name "*.md" | rev | cut -f1 -d "/" | rev | cut -f1 -d "." 
NOT find . -type f -name "*.md" | rev | cut -f1 -d "/" | rev | cut -f1 -d "." 
NOT find . -type f -name "*.md" | rev | cut -f1 -d "/" | rev | cut -f1 -d "." 
