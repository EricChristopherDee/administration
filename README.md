# administrationnotes

....... Windows === 
-
The course instructor uses powershell

hidden files quick reference: its found in the view tab

ls -force shows hidden

~ is a shortcut for home directory

typing .\ then tab allows cycling through locations from current directory

history shows a history of commands

ctrl + r or #command can cycle through previous commands

clear clears the screen (powershell)

cls in command prompt ..

cat shows contents of file

more shows all contents with a prompt for each section

cat -head or cat -tail with a number ie cat -head 10 shows the file up to those lines, like more does 

=== Linux === 
-
linux has two operations for "help"

man (command name), and (command name) --help

ls -l shows extra details, and stands for long
   -a shows hidden
   
history does the same thing

clear clears the screen

head name of file
tail name of file shows only 10 lines each

2> removes error messages from a pending output

| passes output from one command to another new command
   ie ls folders | grep specific folder to check if a folder exists in a directory
   
cat shows the contents of a file if not concatenating multiple files

   Recap:
      ls - l shows extra info like ownership
      ls - a shows hidden files
      pwd brings you the current directory
      single file cat shows the contents
      less allows easier reading of files with many characters
      multiple directories can be made with a single mkdir command using spaces
      
      mkdir:  
         -p: allow mkdir to create parent directories if they don't exist
         -m: (mode) used to set permissions of directories during creation
         -v: run command in verbose mode
     
     touch:
         -c doesn't create if already exists
         
     grep:
     
       -r: search recursively
       -w: match the whole word
       -n: only in line number
       -e: match pattern
       --include and --exclude: include and exclude files in the search
       --include-dir and --exclude-dir: include or exclude directories in the search

==== Both ====
-
pwd means print working directory
