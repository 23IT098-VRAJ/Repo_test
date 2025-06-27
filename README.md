# Repo_test

i'm learning the GITHUB

1. ls -> to get all files.
2. ls -force -> to get all files(including hidden).
3. git status -> to get repo status.
4. files with M -> MODIFIED, U -> UNTRACKED(new file), S -> STAGED(U file got add but not updated), UN -> UNMODIFIED.
5. ls -> to get all files.
6. git add <FILENAME> (To add all files or all changed files to working DIR ).
7. git add . (To add all files or all changed files to working DIR ).
8. git commit -m "SOME SORT OF MSG" (Record of change).
9. git push origin main -> to upload local repo to remote repo.
10. cd -> to go to sun dir, cd .. -> to go back once.
11. git init -> used to create a new git repo.
12. git remote add origin -> To add a new remote repo.
13. git remote -v -> to verify the repo link.
14. git branch -> to check the branch.
15. git branch -M main -> to rename main branch.
16. git push -u origin main -> where -u stands for upstream it means we r letting it knoe that we just want to work on origin main for a long time so from next time we can only  "git push" to push the codes to repo.  
-> Now if we are doing grp project / to add new feature, we need to do different works and we cant wait for others to complete 1st so we make new branches and do our work in that perticular branch.
17. git checkout -b <branchname> -> to create a new branch(To work in grp).
18. git checkout <branchname> -> to navigate (In which branch u want to go).
19. git branch -d <branchname> -> to delete branch.
-> Now work has done! we need to merge the code to the main branch with 2 way.
20. git diff <branchname> -> to get the diff of commits,branches,files n more of currant and the other branch's.
21. git merge <branchname> -> to merge the currant and the other branch.
22. with PR (preffer this) -> Pull Request
-> Now with this PR we branches are merged at remote so we have to locally too.
23. git pull origin main -> to get changes occured at remote (merging).
-> Now what about Merge Conflict(where in both branch on the same file are filled with some different code). Don't worry my boi!! In this condition you have to use the command "git merge <branchname>" and then VS CODE will give us 4 options to choose the ways that how we want the changes.
-> Now we human so mistakes are in our blood, it will for sure and knowingly-unknowingy we can commit changes but again we have facility to undo our
mistake.
24. 
Case-1:Staged changes
1. git reset <filename> -> For perticular file.
2. git reset -> for many staged files.
Case-2:Commited changes(1 commit)
1. git reset HEAD~1 
Case-3:Commited changes(For the multiple commits we have to check the log and have to get that peeticular HASH of that commit to go back there)
1. git reset <commit hash>(hash of that commit)
2. git reset --hard <commit hash>(It will change(remove) the commited code even from the vs code(any editor))
25. git log -> To check all commits.
26. Fork(it's a rough copy of somebody else's repo) -> 1st of why to do this when we can clone it right? Well we can make a direct copy to our git hub acc repo with same name / names by us but the same repo content while with clone we have to upload it manually. Now how to do it so we have to get link of that repo 1st and then have to open it and on the right side above the middle and a little bit down from top you will see the option for FORK. 
**YOUR ULTIMATE GITHUB TRIP IS OVER NOW ENJOY MY BOI!!**