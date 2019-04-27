##########Problem Statement ###############


Three Developersare working in Aperture Technology co. . Their company want a better Source Code Management Systembecause the earlier tool had the tendency to save redundant code. Multiple Developers working simultaneously on same block of code also caused problems. You are Mike, and your manager has given you the task of moving the company’s code base to git and Github. 



Action Items:


•Create alocal git repository and move the entire code base to it.

•Create a new branch for a new feature you want to add to the application.

•Merge back the created branch with the master branch•Create a remote repository.

•Push the local repository to company’s remote repository







Link to download the code : 

https://github.com/rkidambi11/Assignment_Git/blob/master/sample-project.zip 





#### Solution ##############

Module 1 : Version Control -GIT
1. Move to your Source Code directory and initialize a git repo in that folder
 Syntax: git init

2.Add all the files in the repository to the staging area
Syntax: git add .

3.Now commit these files to the local repository
Syntax: git commit

4. Create a new feature branch and switch to it
Syntax: git branch branchName
 git checkout branchName

5. Make the required changes to the source files and the do a git diff to check all the changes
Syntax: git diff

6. Now add the changed files to the staging area
Syntax: git add fileName
 OR git add .
7. Commit the changes
Syntax: git commit

8. Now switch back to master and merge the feature branch back into master
Syntax: git merge branchName

9. Now, create a remote repository on you Github account.

10. Add the remote repository to you local repo.

Syntax: git remote add origin repoURL

11. Push the local repository onto the remote Repository
Syntax: git push -u origin master
