# Git_Basics
## Names:
1. Dyohan
2. 
## Initializing
1. Open your root folder
2. ```git init``` to initialize an empty local repo
3. ```git remote add <any name> <repo link>``` to add your repo from github.com
4. ```git pull <the name u used> <branch_name>``` to add changes from your repo to your local machine

- the name you use is not neccesarily the repo name it could be any name

## "Pulling" from your repo
1. ```git pull <the name u used> <branch_name>```
2. thats really it lol

## "Pushing" changes to your repo
1. open the root folder
2. open your CLI
3. ```git add .``` to use all files to "push"
4. ```git commit -m "<commit name>"``` to create a new "commit"
5. ```git push <the name you used> <branch_name>``` to "push" or upload your changes to your repo

- make sure the branch you are pushing to is the same branch on your local repo
- if unsure with what branch you are on u can use ```git branch``` to see what branch you are currently on
to switch branches user ```git branch -m <current branch> <target branch>```
