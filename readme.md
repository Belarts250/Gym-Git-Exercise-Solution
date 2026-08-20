# This project is about Git exercise solutions

## Bundle 1

### Exercise 1

```bash 

PS D:\learn\Gym-Git-Exercise-Solution> 
PS D:\learn\Gym-Git-Exercise-Solution> mkdir Git-solutions


    Directory: D:\learn\Gym-Git-Exercise-Solution


Mode                 LastWriteTime         Length Name                
----                 -------------         ------ ----                
d-----        20/08/2026     19:22                Git-solutions       


PS D:\learn\Gym-Git-Exercise-Solution> cd Git-solutions
PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git init
Initialized empty Git repository in D:/learn/Gym-Git-Exercise-Solution/Git-solutions/.git/
PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git branch -M main

PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)
PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git add readme.md
PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git commit -m "Initialisation of the project"
[main (root-commit) 12b291b] Initialisation of the project
 1 file changed, 1 insertion(+)
 create mode 100644 readme.md
PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git remote add origin https://github.com/Belarts250/Gym-Git-Exercise-Solution.git
PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git push --set-upstream origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 274 bytes | 91.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Belarts250/Gym-Git-Exercise-Solution.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git checkout -b dev
Switched to a new branch 'dev'
PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git push --set-upstream origin dev 
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Belarts250/Gym-Git-Exercise-Solution/pull/new/dev
remote: 
To https://github.com/Belarts250/Gym-Git-Exercise-Solution.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.
PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git checkout -b test
Switched to a new branch 'test'
PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/Belarts250/Gym-Git-Exercise-Solution/pull/new/test
remote: 
To https://github.com/Belarts250/Gym-Git-Exercise-Solution.git
 * [new branch]      test -> test
 PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git checkout dev
M       readme.md
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.
PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> git branch -D test

Deleted branch test (was 12b291b).
PS D:\learn\Gym-Git-Exercise-Solution\Git-solutions> 
```