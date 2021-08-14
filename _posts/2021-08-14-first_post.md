## Git commands

Imagine you are working in a team, there is a team lead above you. You guys are creating code for your projects. Sometimes you work in teams or you might be also have individual sub project. Team Leader needs to know about all the coding changes are happening. Team members need to create branch from the master and develop their changes and push the branch to the server. Then, you can notice a create Pull request option, which allows the changes you made to merge on to the master. After creating the Pull request(called as PR in tech teams for short), Team lead looks over your changes and if there aren't issues, he will do the merge without any conflicts.


Let's look at the git commands you use throughout this process


`git branch -b mybranch01`  - Creates a branch on your local repository with the branch name as **mybranch01**
`git checkout mybranch01`  - After running this command, code you notice in the project folder will point to mybranch01

After making your changes, you need to stage them for committing.

`git add -A` - Stages your code 
`git commit -m "describe the changes in this commit"`-  commits your changes, it just means that your changes are finalized and ready to push to server. So be careful before committing.
`git push origin mybranch01` - Push your branch to the online repository and your team can view your code and now create a PR and request your Team Lead to merge the changes.




Things to Add:
1. Squash the commits
2. Add pictures to understand this flow for a new github user


