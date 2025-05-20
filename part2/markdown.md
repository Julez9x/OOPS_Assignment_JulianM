## 1. List three major version control software for software engineering. 

- Git
- CVS
- Mercurial

## 2. What are the main advantages to using Git in your software development, and how is it useful for game developers.

A place where you can save your development process and keep an alternative copy in a different location i.e. backing up in a different location. Useful to distribute to different people who are working on the project which can be for different sections/parts of the project and work on the whole together.

## 3. Define the following terms in relation to Git. Branch, Pull, Push, repository, working copy, merge.

Branch - Different locations for different stages of your process.
Pull - Download files from Github.
Push - Finalises upload to Github.
Repository - Copy of a codebase.
Merge - Merge different files/branches together.

## 4. If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.

>Acceptable Use\
>Password Security\
>Data Protection and Privacy\
>Remote Work\
>Data Backup Procedures\
>Risk Management\
>Organisational Efficiency

## 5. Merge conflicts can occur while using Git. List merge tools or diff tools you can use to help you merge and deal with conflicts.

VSCode, VimDiff, P4Merge and JetbrainRyder.

## 6. In a merged source code file, how does Git let you know there is a conflict?

Lines and arrows indicate the difference between the original code and the new updated code. This will be indicated at the start and end of conflicting sections and seperate the conficts made from different branches.

## 7. What are the steps you can take to resolve Git conflicts?

Identify the conflict as shown with the indication markers ">> << == ==", open and edit how you would like the upload to be, resolve said conflict by deleting the markers, add the file back if needed then finally commit and push your merge to finalise.

## 8. What does git revert do, and how can you use it?

Undoes a commit to remove changes to that commit. You can go back to a previous commit without having to undo lots of other changes.

## 9. What does git reset do, and how can you use it?

Moves current position on repo to a different point in the process. You can rewind back to a previous state of a project before potential bugs or issues.

## 10. What is the difference between git revert and git reset?

Reset goes back to a different location in repo whilst the other one just reverts changes to a commit.

## 11. True or False: Is it okay to commit broken code to the main branch?

False

## 12. True or False: You should commit related changes. For example, fixing two different bugs should produce two separate commits.

True

## 13. Describe what is DevOps, how is it useful for game developers?

A number of different phases which are used to create and develop programs/features. It is useful for game developers because it is a way to rapidly produce work whilst maintaining a consistent flow which can help production and rate of work.

## 14. List what tools can be used with DevOps. Give a brief description of each one. (at least 3)

Github - Automation tool where developers can quickly edit and upload existing code. \
Jenkins - Testing tool which helped develop, handle and deliver the product and this requires fast and precise solution so the repetition continues. \
Buddy - Pipeline (CI/CD) tool which automates code upgrades and ensures changes are consistent with most recent code version.

## 15. What is CI/CD and how can it be used to automate the game development process.

Continuous Integration and Continuous Delivery/Development - Detects any changes in the code version either updating it automatically or making you aware of changes. Makes sure the code will work on newer versions without you having to rewrite code.
