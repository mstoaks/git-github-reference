### Start with a github repo then clone it to a local machine
1. Create the repo on github
2. Create a directory on local
3. On local machine - `git clone <path to git repo> <where you want the dir>`

### Start with github repo then create a local repo sync'd to it
1. Create the repo on github
2. Create a directory on local machine, run git init
3. On local machine - `git remote add origin <path to git repo>`
4. On local machine - `git pull origin master`

### To Update Github with Local Changes
`git push origin master`


### To Update local with latest Github
`git pull origin master`

### To Examine Current Git Config
`git config -l`

### To Stage Changes for Commit and Sync to Github
`git add <file that's changed>` OR `git add .` adds all changed files

### To commit
`git commit -m "<your commit message>"`


