
**Beginner Commands :**

01 - Initialize a git repository

```bash
git init
 ```
  
  02 - Add the file into staging area
  
```bash
git add <file>
```
  
  03 - Commit into local repos

```bash
git commit -m <message>
```
  
  04 - Generate a ssh key
  
```bash
ssh-keygen
```

05 - Show the ssh public key

```bash
cat ~/.ssh/id_rsa.pub
``` 

06 - Copy prev ssh-key & paste it onto github ssh authentication

07  - Create repository on github

08 - Copy the ssh-url of that repository

09 - Add a origin of remote repository into local repository

```bash
git remote origin <ssh-url>
``` 

10 - Move from local to remote

```bash
git push origin master
```

**Advanced Commands :**

11 - Move from remote to local

```bash
git pull origin master
``` 

12 -  Create and switch to the new branch

```bash
git switch -c <branch-name>
```

13 - Delete a branch

```bash
git branch -D <branch-name>
```

14 - Merge feature branch with master branch

```bash
git merge <branch-name>
```

15 - Clone the remote repository onto your local repository

```bash
git clone <ssh-url> .
```
