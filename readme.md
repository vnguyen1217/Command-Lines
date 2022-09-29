
#Use in terminal
'git init' to initialize a new repository
'git add' to add files to the staging area
-   'git add .' to add all files
-   'git add -A' to add all files
-   'git add -u' to add all files that have been modified
-   'git add <filename>' to add files interactively
'git commit' to commit changes
-   'git commit -m "message"' to commit changes with a message
'git status' to check the status of your repo
'git push' to push changes to remote repo
-   'git push -u origin <branch-name>' pushes brach to origin
'git pull' to pull changes from remote repo
'git clone' to clone a repo into a new directory



#To setup SSH key with github
'ssh-keygen -t ed25519 -C <comment>' to generate a new ssh key with a comment
'notepad.exe $HOME\.ssh\id_ed25519.pub' to open the public key in notepad   //copy this
-   go to github and hit profile picture in top right
-   go to preferences
-   go to SSH
-   hit new SSH key
-   paste the public key into the key box
-   hit add SSH key
-   'ssh -T git@github' make sure use username //make connection

