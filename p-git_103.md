# project git-103

Here is a simple report of the steps we took to fulfill the project requirements using the rebase concept:

1. Created a new project.
2. Created commit C6, commit C5, commit C2, and commit C1 in the Master branch based on the provided drawing.
3. Created commit C4 and commit C3 in the Feature branch.
4. Created commit C7 and commit C8 in the Feature2 branch.
5. Performed a rebase of the Feature2 branch onto the Master branch using `git rebase --onto`.
6. Checked out the Master branch and merged it with the Feature2 branch.
7. Deleted the Feature2 branch, leaving the Master branch at commit C8.
8. Performed a rebase of the Feature branch onto the Master branch.
9. Checked out the Master branch and merged it with the Feature branch.
10. Deleted the Feature branch.

By following these steps, we successfully completed the project requirements using the rebase concept.
This involved creating commits in different branches, performing rebases,
merging branches, and deleting branches.
