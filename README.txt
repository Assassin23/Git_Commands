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

9. `git remote`: lists down all the remote connection names. Remote connections helps you to link two repositories together for uploading & dowloading changes to each other.

10. `git remote add <name_of_the_remote> <link_of_the_remote>`: it helps us to add a new link to the remote repo and give it a name.

11. `git remote rm <name_of_remote>`: it removes the remote connection.

12.`git remote rename <old_name> <new_name>`: it renames the remote connection.

Note: the name of the remote connection is always used to establish communication between the repos.

13. `git pull <remote_name> <branch_name>`: it downloads latest changes from the branch of the mentioned remote to your local repo.

