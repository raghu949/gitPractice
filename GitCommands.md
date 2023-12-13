# Raghu Ram Practicing Git Commands
#12/11/2023
#Command 1
git init
#This command create .git hidden folder in your main folder, Vh is responsible to track all git commands and track the files in this folder
#Version 1
#Version 2 started
git add <file_name>
git add<space> .
#These commands are used to stagged the untracked files from current dir 
git restore --staged <file_name>
#This command used to unstaged file from staging area to untracked area
git commit -m <Message>
#This command used to transfer the file from staged area to tracking area
#Version 3 added
#git commit will store with SHA1 hash code of 40 Char
#To go back in your commit
#To see hash codes
git log
git reset <HashCode of previous Commit>
git restore <file_name>
#With these two commands you will go back in your file to previous state
git diff <file_name>
#With this command we can found what changes are done in a file unlike git status
git log -p -2
#Last 2 Commits

