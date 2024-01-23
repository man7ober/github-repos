# INSTRUCTIONS

1. git init - intialize a git repository
2. git add <file> - add the file into staging area
3. git commit -m <message> - commit into local repos

## CREATE AN SSH KEY

4. ssh-keygen - generate a ssh key  
5. cat ~/.ssh/id_rsa.pub - show the ssh public key
6. copy prev ssh-key & paste it onto github ssh authentication


7. create repository on github
8. copy the ssh-url of that repo
7. git remote origin <ssh-url> - add a origin of remote repo into local repo
8. git push origin master - move from local to remote 
9. git pull origin master - move from remote to local

## USEFUL COMMANDS

1. git switch -c <branch-name> - it will create and switch to the new branch
2. git merge <branch-name> - this will only work on master branch
3. git clone <ssh-url> - it will clone the repo onto your local repository
