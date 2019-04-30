# Rules develop on github 

> All of that thing about for members of RHP Team. That rules not using be out of.

# How to define name a branch using git?

Create a branch and switch to new branch.

``` git checkout -b dev-name-api```

> Note: name is real name of you. Example: My name is Tran Quoc Toan. I will set dev-name is dev-toantr-api. My name is Nguyen Van Hoang. I will set dev-name is dev-hoangnv-vue

### List name extension of branch
- VueJS: using by `vue`. Example: dev-toantr-vue.
- ReactJS: using by `react`. Example: dev-toantr-vue.
- Api: using by `api`. Example: dev-toantr-vue.

> If you create branch wrong! Leader will delete your branch when review code. U should make do right way.

# How to create new branch from other branch?

In some cases, you start a project from a branch of a colleague or team leader. You should create a branch from that branch, by default git will take the entire code of the current branch and switch to the new branch. So, the best way for you, branch and switch to a new branch to save time as well as unnecessary errors.

```
git checkout dev-newbranch-vue -b
```

> Note: `-b` is stands for branch. 

# How to fix conflict when merge new branch?

Merge branch means that you merge the two branches together, which is often used to merge another branch inot the branch master before pushing to the remote repository, or merge two branches into one to solver the same task.

> When you get a conflict error. You need to make sure the following.

* You need commit code old branch before merge.
* If You and your partner make file same. U need go to file delete code wrong.

**Example: I make branch-a and I want merge code of branch-b to my branch**

```git merge branch-b```

If you don't have a duty to change the code on some else's brnach. You can't push code into their branch. Thank you!
