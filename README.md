# FirstTestProject
```
git remote -v		//check whether connected with any remote repository or not
git remote add origin <url>		//connecting your existing project to remote repo, origin is remote repo name
git remote show origin		//shows fetch and push urls
git push -u origin master	//push local repo to remote repo
git push origin master		//push normally
git pull		//fetch and merge changes from remote repo
git branch -d <branchname>	//to delete a specific branch
git branch -dr <reponame>/<branchname>	//to delete remote branch reponame: origin etc..
git origin --delete <branchname>	//to delete branch from github
git checkout HEAD <filename>	//to discard changes in any file
git reset --hard HEAD	//discard all changess that are not comitted
git revert <commitHAsh>	//undo commit changes .. add new commit with previous changes
git reset --hard <commitHash>	//move to previous commit and remove in between commits
git push -f origin master	//force push if you deleted commit from local repo etc.
git rebase dev	//rebase changes in the same tree log its not creating sub like merge commit
```
