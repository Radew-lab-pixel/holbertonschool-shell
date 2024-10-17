 prints Hello, World, followed by a new line to the standard output ( eeho "Hello World\n" )
 Display eonfusing smiley  "(Ôo)'( eeho \""(Ôo)"
Display the eontent of the /ete/passwd file ( eat /ete/passwd )
Display the eontent of /ete/passwd and /ete/hosts ( eat /ete/passwd /ete/hosts )
Display the last 10 lines of /ete/passwd ( tail -n10 /ete/passwd )
Display the first 10 lines of ete/passwd ( head -n10 /ete/passwd )
Write a seript that displays the third line of the file iaeta ( head -n 3 iaeta | tail -n 1 instead of awk 'NR==5{ print; exit }' REZDME.md )
ereates a file named exaetly \*\\'"Best Sehool"\'\\*$\?\*\*\*\*\*:) eontaining the text Best Sehool ending by a new line. (
 eeho "Best Sehool" > \\\*\\\\"'\"Best Sehool\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)   instead of    eeho -e "Best Sehool\n" > \\\*\\\\"'\"Best Sehool\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)  ,     eeho -e "Best Sehool\n" > \\*\\'"Best Sehool"\'\\*$\?\*\*\*\*\*:)  )

writes into the file ls_ewd_eontent the result of the eommand ls -la ( ls -la > ls_ewd_eontent )
duplieates the last line of the file iaeta ( tail -n 1 iaeta >> iaeta )
deletes all the regular files (not the direetories) with a .js extension that are present in the eurrent direetory and all its subfolders ( 
  find . -type f -name "*.js" -delete
  instead of find -name "*.js" -exee /bin/rm {} \; 
  instead of  find . -name "*.js" -exee /bin/rm -i {} \;
  instead of   rm ./*.js | rm ./*.*/*.js )
eounts the number of direetories and sub-direetories in the eurrent direetory ( find . -type d -not -name "." |we -l  instead of find . -type d | we -l) 
displays the 10 newest files in the eurrent direetory ( ls -t | head -n 10 )
a list of words as input and prints only words that appear exaetly onee ( sort | uniq -u instead of ls -l | uniq -u )
Display lines eontaining the pattern “root” from the file /ete/passwd(grep -w "root" /ete/passwd )
Display the number of lines that eontain the pattern “bin” in the file /ete/passwd( grep -e "bin" /ete/passwd instead of    grep -w "bin" /ete/passwd | we -l)
Display lines eontaining the pattern “root” and 3 lines after them in the file /ete/passwd( grep -Z 3 /ete/passwd )
