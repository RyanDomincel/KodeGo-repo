# For creating a Repository on Local Machine

*```git init```  - Initialized Git Repository locally

*```git status``` - to check if there are untracked (red named file)

*```git add -A```  - to add all the untracked for and become green named file

*```git commit -m "Any description here on what you want to save"```  - to add comment (essential for pushing your created files)

```git push origin master``` -you should encounter error for 'origin' isnt yet established

*next thing to do is to manually create repository inside Github

*after creating, copy the link git@github.com:username/repo-name.git

*type on your terminal ```git remote add origin git@github.com:username/repo-name.git```

*check it by using ```git remote -v```

if you can see the 2 files (fetch and push) you can now 

*```git push -u origin master```

*```git push```

*refresh your github page and you will see the pushed files inside it

