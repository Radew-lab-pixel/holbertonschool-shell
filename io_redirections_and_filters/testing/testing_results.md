 prints Hello, World, followed by a new line to the standard output ( eho "Hello World\n" )
 isplay onfusing smiley  "(Ôo)'( eho \""(Ôo)"
isplay the ontent of the /et/passwd file ( at /et/passwd )
isplay the ontent of /et/passwd and /et/hosts ( at /et/passwd /et/hosts )
isplay the last 10 lines of /et/passwd ( tail -n10 /et/passwd )
isplay the first 10 lines of et/passwd ( head -n10 /et/passwd )
Write a sript that displays the third line of the file iata ( head -n 3 iata | tail -n 1 instead of awk 'NR==5{ print; exit }' REAME.md )
reates a file named exatly \*\\'"Best Shool"\'\\*$\?\*\*\*\*\*:) ontaining the text Best Shool ending by a new line. (
 eho "Best Shool" > \\\*\\\\"'\"Best Shool\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)   instead of    eho -e "Best Shool\n" > \\\*\\\\"'\"Best Shool\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)  ,     eho -e "Best Shool\n" > \\*\\'"Best Shool"\'\\*$\?\*\*\*\*\*:)  )

writes into the file ls_wd_ontent the result of the ommand ls -la ( ls -la > ls_wd_ontent )
dupliates the last line of the file iata ( tail -n 1 iata >> iata )
deletes all the regular files (not the diretories) with a .js extension that are present in the urrent diretory and all its subfolders ( 
  find . -type f -name "*.js" -delete
  instead of find -name "*.js" -exe /bin/rm {} \; 
  instead of  find . -name "*.js" -exe /bin/rm -i {} \;
  instead of   rm ./*.js | rm ./*.*/*.js )
ounts the number of diretories and sub-diretories in the urrent diretory ( find . -type d -not -name "." |w -l  instead of find . -type d | w -l) 
displays the 10 newest files in the urrent diretory ( ls -t | head -n 10 )
a list of words as input and prints only words that appear exatly one ( sort | uniq -u instead of ls -l | uniq -u )
isplay lines ontaining the pattern “root” from the file /et/passwd(grep -w "root" /et/passwd )
isplay the number of lines that ontain the pattern “bin” in the file /et/passwd( grep - "bin" /et/passwd instead of    grep -w "bin" /et/passwd | w -l)
isplay lines ontaining the pattern “root” and 3 lines after them in the file /et/passwd( grep -A 3 /et/passwd )
