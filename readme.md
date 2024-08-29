Basic command of Git and Github

	GIT:
1. first initialize the folder or directory: 
	git init
2. check for status which file is add to git repo:
	git status
3. add file to repo:
	git add . -- means all file in folder
	git add <filename> -- particular file
4. check status 
	git status
5. final commit means to save:
	git commint -m "<your message>"
6. use .gitignore file to ignore the file which you didnt want to push it into repo
	create .gitignore file and add the name of the file you want git ignore that file
7. if you created an empty folder but you want to push the empty folder. You know that empty folder will be used at the end.
	create .gitkeep file in your empty folder. Git will keep that folder.
	If you dont use that file in your empty folder. Git will ignore the folder.
8. create a new branch:
	git create <branch-name>
9. use branch
	git switch <branch-name>
10. If you are working with new branch. Now you want to make the changes you made to new branch to apply to main/master branch:
	git merge <branch-name>

	GITHUB:
11. Create SSH for your personal github account. If already created well and good.
12. Create a repo where you want to push your code online.
13. Copy the html path of repo: "https://github.com/Sufiyan75/Git_Demo.git"
14. Complete all steps till commit and after commit run the command to add origin to path
	git remote add origin https://github.com/Sufiyan75/Git_Demo.git
15. To check status of origin (origin is a name which we choosed)
	git remote -v
16. If you want to remove current origin:
	git remote remove origin