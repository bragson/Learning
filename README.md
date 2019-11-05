# From new:

1. `git clone`

2. `git add <filename>`

3. `git commit -m "<message here>"`

4. `git push --set-upstream origin master`

# If Making Repo From Existing Local Project:

1. `cd` to project directory

2. `git init`

3. `git add <filename>`

4. `git commit -m "<message here>"`

5. Make repo on version control site and copy the `"git remote add origin <url>"`

6. `git push --set-upstream origin master`

# For issues of existing repo:

1. make branch for issue.

    *    `git checkout -b <name>`
    *    `git push --set-upstream origin <name>`

2. make needed changes (could be one or more commits locally)

3. after last change, do final 'git push'

4. go to version control site > pull request > create new pull request.

5. PR reviewer makes comments

6. Developer makes commits to satisfy those comments

7. PR reviewer approves PR 

8. Merge to master

9. `Git checkout master` in terminal

10. then `git pull`


11. repeat

[Markdown help](https://dillinger.io/)
