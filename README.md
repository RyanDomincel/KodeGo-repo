# For creating a Repository on Local Machine

1. `git init`  - Initialized Git Repository locally

2. `git status` - to check if there are untracked (red named file)

3. `git add -A`  - to add all the untracked for and become green named file

4. `git commit -m "Any description here on what you want to save"`  - to add comment (essential for pushing your created files)

5. `git push origin master` -you should encounter error for 'origin' isnt yet established

6. next thing to do is to manually create repository inside Github

7. after creating, copy the link git@github.com:username/repo-name.git

8. type on your terminal `git remote add origin git@github.com:username/repo-name.git`

9. check it by using `git remote -v`

if you can see the 2 files (fetch and push) you can now 

10. `git push -u origin master` or `git push`

11. refresh your github page and you will see the pushed files inside it

