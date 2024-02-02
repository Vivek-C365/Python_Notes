# Read me File
- let see how Git Works
- this is new line now try add  it to the file and commit  it.

# Commands used in class:
bash git_basics.sh
git status
cat README.md
nano README.md (to edit)
git diff --color-words HEAD -- README.md
git add README.md
git commit -m "Added a new line"
git log

## Explanation of commands:
`bash git_basics.sh`: This command runs the script `git_basics.sh`, which contains instructions for the class. It sets up a local repository, creates a remote
**`bash git_basics.sh`:** This command runs the script `git_basics.sh`, which contains instructions for creating a local repository, adding files to it, making

## Explanation of Branching:

**Now i am in main branch**

**Creating a branch:** `git checkout -b <branchname>`
This command creates a new branch named `<branchname>`. The `-b` flag tells Git that you want to create a new branch if it doesn't exist, otherwise switch to it.

- Now i am in  master branch, which means that all my changes will be made here.
- If you want to make any change without affecting anything else, you can create a new branch using following command:
- To create a new branch use `git checkout -b <new_branch_name>`. This command will switch to your new branch and you'll start making changes there instead of on If you want to make any change then first switch to another branch using `git checkout <branchname If we want to make any change then first we have to switch to another branch using `git checkout If we want to make any change then first we have to switch to another branch using `git checkout
- To create a new branch use `git checkout -b <branch name>`. For example: `git checkout -b feature/newFeature`
- To create a new branch use `git checkout -b <branch name>` command. For example: `git checkout -b feature/newFeature`
- To create a new branch use `git checkout -b <branch name>`
- If you want to switch back to your master branch use `git checkout master`
- You can list all branches with `git branch` or `git branch -a` for listing both local and remote branches.
- When you make changes on one branch and then switch to another, these changes are not lost because they are still stored in your computer's memory. So if you want to get rid of
- When we make a change on one branch and then switch to another, our change follows us. This concept is called detaching head. We can avoid this by using `git checkout --det
- When you make changes on one branch and then switch to another, these changes are not lost. They remain there until you decide to merge them into the other branch or delete them.