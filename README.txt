Git commands with brief description:

1. `git add <file_name>`: moves the file from working area to staging area.

2. `git rm --cached <file_name>`: moves the file from staginf area to working area.

3. `Commit`: - It is a particular version of the project.it captures a snapshot of the changes in the staging area and makes a version from it.

4. `git commit`: registers staging changes to a commit. we use -m flag to give the commit message and not have git open atext editor. [`git commit -m "<your_commit_message>".`]

5. `git log`: it lists down all the commit of the repository.

6. `git restore <file_name>`: it removes all file changes from the woking area to be staged. To remove changes from staging area, we will use the `--staged` option.

7. Diff between git rm & git restore.
- if we want to move a whole file back to the working area but restore only moves the changes to either working or staging area.

8. `git diff commit1 commit2`: gives the difference between the two commits.


