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
-> Now work has done! we need to merge the code to the main branch.
20. git diff <branchname> -> to get the diff of commits,branches,files n more of currant and the other branch's.
21. git merge <branchname> -> to merge the currant and the other branch.