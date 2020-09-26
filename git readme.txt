Starting wisth a pre created Project consist of files
1. right click on folder and open witn Git Bash
2. Initiallize by writing Command ==> git init
	2 (i) Addding User's Name and email by
	==> git config --global user .name "Rajendra"
	==> git config --global user .email "rchoudhary157@gmail.com"
3. Adding files to local repository ==> git add .html or .txt ot .(All or *)
4. Check status ==> git status
5. Commiting with comments ==> git commit
6. After git commit it opens a new screen, press i then commit by #Some Coomment
7. To exit commit screen press ==> ESC then :wq
8. To commit Directly ==> git commit -m "Some comment" (-m means message)
9. to remove a file ==> git rm --cached index.html(filename with extension)
10. Creating a file ==> touch index.html(Filename With extension)
11. Creating git ignore ==> touch .gitignore (this file contains ignored files by git or untracked files.)
12. In .gitignore write file name of which we dont want to be tracked (generally log files or debug files) ==> log.txt, dir/
13. For creating remote repository ==> create repository on GitHub or any then read instructions
14. Create readme.md (md = mark down)
15. git remote will give you the list of remote repositories
16. For adding remote repositories ==> git remote add origin https://github.com/something
17. For start adding files copy these code ==> git push -u origin master (login to repository if not)
18. Your files will be added. then after that simply push file remotely by ==> git push
19. Creating branches which is diffrent part of that repository. any changes in branch will not reflect on master
20. Start creating branch ==> git branch login(Any name of the branch)
21. Switch to the branch ==> git checkout login(Branch name)
22. Creating file in branch ==> touch login.html //Changes in this brach not reflect to master even if you change master files
23. Switch to matser ==> git checkout master ==> this will remove branch's file from your local but you can switch any time to branch this will restore your branch.
24. Merging branch and master ==> In master ==> git merge login(branch name), this will open a new sceen like commit
25. Add comment for merging your branch this will help you later Now you can see all folders in same branch and you can modify all files in master