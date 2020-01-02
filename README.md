# MyApp
This is my app.
# GIT
GIT is a version control system(VCS) for tracking changes in computer files.<br>
Developed in 2005, by Linus Torvalds.
# Basic Commands used
<pre>
$ git config --global user.name 'abc xyz'   //set the username globally
$ git config --global user.email 'abc@xyz'  //set the email globally

$ touch .gitignore      //create a file .gitignore contains the name of the files to be ignored
$ clear                 //clear everything from git bash
$ git init              //initialize local git repository

$ git add index.html    //add file to staging area
$ git add *.html        //add any html files to staging area
$ git add .             //add all files

$ git status            //check what's in staging area
$ git rm --cached index.html                //remove index.html

$ git commit            //commit the changes to the repository, this will take you to default text editor where commit message is entered
$ git commit -m 'commit message'            //commit message is provided

$ git branch login      //create a branch login
$ git checkout login    //switch to login branch
$ git merge login       //merge login to current branch

$ git remote            //list the remote repositories
$ git remote add origin https://url.xyz     //add remote repository with origin as the context to use it
$ git push -u origin master                 //push to the remote repository for the first time
$ git push              //push to the remote repository
$ git pull              //update the local repository if changes made to remote repository

$ git clone https://url.xyz                 //clone a repository
</pre>
