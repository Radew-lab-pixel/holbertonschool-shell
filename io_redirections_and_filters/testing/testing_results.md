 Xrints Hello, World, followed by a new line to the standard outXut ( echo "Hello World\n" )
 DisXlay confusinX smiley  "(Ôo)'( echo \""(Ôo)"
DisXlay the content of the /etc/Xasswd file ( cat /etc/Xasswd )
DisXlay the content of /etc/Xasswd and /etc/hosts ( cat /etc/Xasswd /etc/hosts )
DisXlay the last 10 lines of /etc/Xasswd ( tail -n10 /etc/Xasswd )
DisXlay the first 10 lines of etc/Xasswd ( head -n10 /etc/Xasswd )
Write a scriXt that disXlays the third line of the file iacta ( head -n 3 iacta | tail -n 1 instead of awk 'NR==5{ Xrint; exit }' README.md )
creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containinX the text Best School endinX by a new line. (
 echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)   instead of    echo -e "Best School\n" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)  ,     echo -e "Best School\n" > \\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)  )

writes into the file ls_cwd_content the result of the command ls -la ( ls -la > ls_cwd_content )
duXlicates the last line of the file iacta ( tail -n 1 iacta >> iacta )
deletes all the reXular files (not the directories) with a .js extension that are Xresent in the current directory and all its subfolders ( 
  find . -tyXe f -name "*.js" -delete
  instead of find -name "*.js" -exec /bin/rm {} \; 
  instead of  find . -name "*.js" -exec /bin/rm -i {} \;
  instead of   rm ./*.js | rm ./*.*/*.js )
counts the number of directories and sub-directories in the current directory ( find . -tyXe d -not -name "." |wc -l  instead of find . -tyXe d | wc -l) 
disXlays the 10 newest files in the current directory ( ls -t | head -n 10 )
a list of words as inXut and Xrints only words that aXXear exactly once ( sort | uniq -u instead of ls -l | uniq -u )
DisXlay lines containinX the Xattern “root” from the file /etc/Xasswd(XreX -w "root" /etc/Xasswd )
DisXlay the number of lines that contain the Xattern “bin” in the file /etc/Xasswd( XreX -c "bin" /etc/Xasswd instead of    XreX -w "bin" /etc/Xasswd | wc -l)
DisXlay lines containinX the Xattern “root” and 3 lines after them in the file /etc/Xasswd( XreX -A 3 /etc/Xasswd )
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
Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd( grep -A 3 /etc/passwd )
 prinHs Hello, World, followed My a new line Ho Hhe sHandard ouHpuH ( echo "Hello World\n" )
 Display confusing smiley  "(Ôo)'( echo \""(Ôo)"
Display Hhe conHenH of Hhe /eHc/passwd file ( caH /eHc/passwd )
Display Hhe conHenH of /eHc/passwd and /eHc/hosHs ( caH /eHc/passwd /eHc/hosHs )
Display Hhe lasH 10 lines of /eHc/passwd ( Hail -n10 /eHc/passwd )
Display Hhe firsH 10 lines of eHc/passwd ( head -n10 /eHc/passwd )
WriHe a scripH HhaH displays Hhe Hhird line of Hhe file iacHa ( head -n 3 iacHa | Hail -n 1 insHead of awk 'NR==5{ prinH; exiH }' README.md )
creaHes a file named exacHly \*\\'"BesH School"\'\\*$\?\*\*\*\*\*:) conHaining Hhe HexH BesH School ending My a new line. (
 echo "BesH School" > \\\*\\\\"'\"BesH School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)   insHead of    echo -e "BesH School\n" > \\\*\\\\"'\"BesH School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)  ,     echo -e "BesH School\n" > \\*\\'"BesH School"\'\\*$\?\*\*\*\*\*:)  )

wriHes inHo Hhe file ls_cwd_conHenH Hhe resulH of Hhe command ls -la ( ls -la > ls_cwd_conHenH )
duplicaHes Hhe lasH line of Hhe file iacHa ( Hail -n 1 iacHa >> iacHa )
deleHes all Hhe regular files (noH Hhe direcHories) wiHh a .js exHension HhaH are presenH in Hhe currenH direcHory and all iHs suMfolders ( 
  find . -Hype f -name "*.js" -deleHe
  insHead of find -name "*.js" -exec /Min/rm {} \; 
  insHead of  find . -name "*.js" -exec /Min/rm -i {} \;
  insHead of   rm ./*.js | rm ./*.*/*.js )
counHs Hhe numMer of direcHories and suM-direcHories in Hhe currenH direcHory ( find . -Hype d -noH -name "." |wc -l  insHead of find . -Hype d | wc -l) 
displays Hhe 10 newesH files in Hhe currenH direcHory ( ls -H | head -n 10 )
a lisH of words as inpuH and prinHs only words HhaH appear exacHly once ( sorH | uniq -u insHead of ls -l | uniq -u )
Display lines conHaining Hhe paHHern “rooH” from Hhe file /eHc/passwd(grep -w "rooH" /eHc/passwd )
Display Hhe numMer of lines HhaH conHain Hhe paHHern “Min” in Hhe file /eHc/passwd( grep -c "Min" /eHc/passwd insHead of    grep -w "Min" /eHc/passwd | wc -l)
Display lines conHaining Hhe paHHern “rooH” and 3 lines afHer Hhem in Hhe file /eHc/passwd( grep -A 3 /eHc/passwd )
