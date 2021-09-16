# Team Git Exercise

This exercise is very similar to the individual GitHub exercise. Make sure each team member has completed that exercise before attempting this one.

1. Come up with a small programming project for the team
2. Have each team member set up git on their own machine 
3. Make sure all team roles are defined 
4. Have the **Tech Lead** setup the team git repo for this exercise. Follow the [Git Basics Tutorial](https://github.com/brandongk-ubco/gitstats/blob/develop/docs/technical/git_basics.md) so that you can ensure the repo is setup in a way that follows the required development flow. Some features require a pro GitHub account, which can be obtained using [GitHub for Education](https://education.github.com/pack) and your school email address (which you may need to use for your repo as well). 
5. Think of at least 1 independent feature per team member that your project will accomplish. Assign each team member one of these features. 
6. Have each member clone the repo locally onto their own machines. 
7. For each feature you are developing in this exercise, have the assigned team member:
  - Switch to the master branch and pull master from the remote repo (origin)
  - Create a branch locally for the feature you are developing. Name it by the feature name, not your own name.
  - Switch to the correct feature branch, merge master into the feature branch (if required).
  - Push the new branch to the remote repo and observe it exists in the branch list.
  - Develop the feature locally. Make sure the feature works by writing at least one test case for it. Commit it to the local feature branch.
  - Make sure to create or update README.md with instructions on what your feature is and how to use it.
  - You should become familiar with the [definition of done](https://github.com/brandongk-ubco/gitstats/blob/develop/docs/technical/agile.md) in the agile framework.
  - Push the feature branch to the feature branch on the remote repository (origin).
  - Create a pull request in the remote repo on GitHub from the feature branch to the master branch. You can make the pull request for someone in the team to review, or to a specific team member. This will help to ensure that someone else has double checked your work and so that it is considered "done".
  - It is your responsibility to address and resolve all the comments and issues raised in the pull request.
  - When you are sure your feature is completed, merge the pull request. This will merge all the work from feature onto the repo's master.
  - The **"first-to-merge-wins"** rule: Because others may have been working on this exercise and pushing their work onto the remote repo, the files you worked off of may now be outdated. Resolve any merge conflicts by pulling master and merging into the feature branch onto your local machine. Be sure to respect other team members' work; this means, you cannot simply overwrite their work with your old files and you must resolve the merge conflicts by ensuring their work is not negatively impacted by your merge.
  - Pull (checkout) the master branch on your local machine and make sure it updates with the code from GitHub. (In general, you will want to do this regularly during your development work so your code base is always up-to-date.)
  - Re-do any tests that had passed previously on the master branch, and ensure they still pass now. Fix any problems necessary and create a new pull request to resolve them.
8. Throughout this exercise, you will need to do pull request reviews. When your teammate finishes a task, someone else will need to verify that it is done at the level of quality that has been agreed up on amongst the team. That means, the code needs to be written following the same standards, it needs to be clearly documented, any design changes need to be updated as part of the task, and the code needs to have passed all the tests as well. Be sure you are familiar with the definition of done (Links to an external site.) in the agile framework. 
9. Grading: **run gitstats and submit the report in PDF INDIVIDUALLY by Friday 24 8:00am (no lates accepted)**
10. Note that in order for gitstats to generate the scores properly, you will need to add issues to your repo (make sure you use one of these labels: task, chore, or exploration). If you have problems see [the FAQ](https://github.com/Gemarodri/Capstone499/blob/main/Resources/RunGitStast.md#faq) 
11. For the purposes of this exercise, just add them with your pull requests after the fact to get gitstats working. In the course project, you can practice the project management side of things properly and make issues from the beginning.
