[Home Page](README.md)

# Git Repositories

## What is a Repository?
They are files contained within a project which can be maintained on GitHub and/or your computer in a Terminal or Command Line. 

## What is the difference between Git and GitHub?
- **Git:** A version-control system which tracks changes during software development and is also a command line tool.
- **GitHub:** A web-based repository hosting service which also has version control.

## How do you set up a Git Repository to work on your text editor and your computer's terminal?

 1. Go to your existing repository, look to the right and you should see a green button which says "Code". 
 2. Click on it and you should get a dropdown that says "Clone with HTTPS". Copy the link that shows.
 3. Go to your Terminal and make sure you are in the directory you want to be. In this case you need to be in Desktop. To change your directory simply type in your terminal the command "cd Desktop". The Terminal is case sensitive so make sure you watch for capitals.
 4. Now, we are going to want to clone your repository so it will show on your Desktop. To do this type this command into your Terminal, "git clone (your site link you copied in step 2)
 5. To see if it is now on your Desktop you can do "ls" which will show all of the files that are on your Desktop.
 6. Now you are going to want to change your directory from Desktop to the name of your file that you have just created.
 7. When you type "ls" into your Terminal you should see the files that are in your repository that show in GitHub. 
 8. You can type the command "git remote -v" which will show all of the remote URLs, you should get a result that shows two links with the word "origin" at the beginning while "(fetch)" is at the end of one of the links and "(pull)" is at the end of the second link. 
 9. You can do "git status" which will show a message which will sometimes have either a green message which indicates you are ready to commit a change or you can get a red message which will say something isn't right. If you get that error message you can solve it by simply typing the command "git add (name of the file that is in red)" 
 10. Type "code ." in your terminal and that should bring up VS Code which is your text editor.
 11. Go into the "README.md" file which should be under the tab with your file name and type some code in there so it can pick up your first edit
 12. Commit your edits that you make by typing the following command into your Terminal "git commit -m "what you have edited and/or why you made the change"
 13. To upload your edit to your website type "git push" and that should have you type in your username and password to GitHub, refresh your website page and boom! Now you can edit your website through VS Code!

## Some commands you will find useful when editing using your Terminal/Command Line.

> We talked about some of these in past notes.

**Command**                      | **What the command does**                                                                               |
:--------------------------------|:-------------------------------------------------------------------------------------------------------:|
cd                               | Change Directory                                                                                        |
git commit -m (any message here) | commits a snapshot of an edit you have made to your repository                                          |
git commit -a                    | commits the snapshots of all edits you have made                                                        |
git push                         | pushes or uploads your local repository changes to your remote repository                               |
git push origin master           | pushes/uploads changes from your local "master" branch to the remote repository which is named "origin" |
git stash                        | when you are not ready to commit changes but you don't want to lose all your progress you've made       |
git stash apply                  | when you are ready to continue working on the changes                                                   |
git init                         | Creates a new repository                                                                                |
git add *.c                      | adds all files with .c extension                                                                        |
git add LICENSE                  | adds a license                                                                                          |
git clone (repository site link) | creates copy of an existing repository                                                                  |
git status                       | tells you which changes have been staged and what is not being tracked                                  | 
git add filename                 | tracks just one file in a repository                                                                    |
git add *                        | tracks all files in a repository                                                                        |
git remote                       | shows all of your connected remote repositories                                                         |
git remote -v                    | shows the URL to your remote repositories and it shows you their short names which is "origin"          | 



