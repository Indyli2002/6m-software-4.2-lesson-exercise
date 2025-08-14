git checkout -b //first creates a new branch, then it swithces to that branch

git branch <branch name>
git checkout <branch name>

-------------------------
1. fork the repository from sctp's main one
2. setup the branch protection rules
3. git clone your repository into your local environment
4. create a feature branch
`git checkout -b <branch name>` // first creates a new branch, then it switches to that branch

`git branch <branch name>`
`git checkout <branch name>`
5. do some random edits like add some text
6. commit your changes `git add; git commit -m "commit message"`
7. push it up `git push`
8. create a PR to merge to `main`
9. review your own pull request
10. merge the pull request 
-----------------------------
Very tricky when doing pr, it will default to ntu repo if we forget to change the base repo to ours, how do I delete the pr that I accidentally created in the ntu repo?

remember to select own repo for the base