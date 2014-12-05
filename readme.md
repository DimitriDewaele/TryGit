# Try Git

## Course

This example folder is a Git Course from:
[https://www.codeschool.com/courses/try-git](https://www.codeschool.com/courses/try-git)

## Git wrong rebase test

 - Create feature branch: feature1 + do some work
 - Push feature1
 - Create feature branch: feature2 + do other work
 - Push feature 2
 - Merge feature2 into master
 - Wrong rebase:
   - rebase feature1
   - pull: this will pull the server feature1 to client: will automatically merge into local rebased branch. (pull = fetch + merge)
   - merge to master
   - push: now you will see a double loop.