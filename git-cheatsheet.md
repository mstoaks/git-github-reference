### Start with a github repo then clone it to a local machine
1. Create the repo on github
2. Create a directory on local
3. On local machine - git clone <pathtogitrepo>

### Start with github repo then create a local repo sync'd to it
1. Create the repo on github
2. Create a directory on local machine, run git init
3. On local machine - git remote add origin <pathtogitrepo>
4. On local machine - git pull origin master

### To Update Github with Local Changes
git push origin master


### To Update local with latest Github
git pull origin master
