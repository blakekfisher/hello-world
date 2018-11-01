Hello world
I am learning git using Git-it
I am learning to add.

To summarize

To start using git in a directory you need to initialize first:

Navigatie to the the directory in the terminal then

git init

To add all of the files in the directory
git add . (space period is importnat here.) If you want to add only certain files git add <filename>

To commit the added files to git repo
git commit -m "your message"

To check that git is working
git status

To check what git has monitored to date
git log

To see the differences to 2 commits
git diff

Github and Git
To connect your git project to a repository on Github

You need a github account

Your git hub username and email should match the one setup in git. To change the username and email in git

git config user.username <your username>
git config user.email <your email>

A note on email. You may need to check your github email settings. If you have set your email to be private you will need to user the git hub privide email in your git settings. You will also need to allow commits from the terminal.

Create repository in Github. Copy the repo url.

To connect local git to remote Github
git remote add origin <gitRepoUrl>

Now you are connect to the repo on Github.

To push the changes from local to git to Github
git push remote origin master
