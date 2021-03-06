# hello-world
Following a [GitHub tutorial](https://docs.github.com/en/get-started/quickstart/hello-world) to learn the basics. 

## _Branch, edit, commit, pull, merge, delete_  
**Step 1:** Create branch of main named "readme-edits". A **branch** is a copy/snapshot of main. You can make and save edits without changing the original.  

**Step 2:** Make some changes to the README file in the "readme-edits" branch of main.   

**Step 3:** Save changes. Saved changes are called **commits**. Each commit has an associated message, a short description describing the changes that were made. These commit messages capture the history of the edits that were made.   

**Step 4:** Submit a **pull request**, which proposes your branch changes to be applied to the original. Pull requests show diffs (differences) between the two branches.   

**Step 5:** Merge. After submitting a pull request, the changes need to be **merged**. After merging, the edits from your branch will be incorporated into main.   

**Step 6:** The last step after confirming the merge is to delete the branch, since it is now identical to main.   


## _Forking_  
A **fork** is a copy of an entire repository, allowing you to make your own changes without affecting the original. Two ways to use forking: 1) use someone else's project as a starting point for your own or 2) propose changes to the original project. Once you fork the original repo, you then must clone it to get the files in that repo to your local computer (otherwise it just exists on GitHub).  
  
See forking practice [here](https://github.com/kyut0/Spoon-Knife).  


## _Git Basics_  
Basic Git commands to know (from [this](https://training.github.com/downloads/github-git-cheat-sheet.pdf) cheatsheet):  

### Branches
**$ git status**  
See what branch you currently have "checked out"  
**$ git branch [branch-name]**  
Creates a new branch  
**$ git checkout [branch-name]**  
Switches to the specified branch and updates the working directory  
**$ git merge [branch]**  
Combines the specified branch???s history into the current branch. This is usually done in pull requests, but is an important Git operation.  
**$ git branch -d [branch-name]**  
Deletes the specified branch  
  
### Create repositories  
**$ git init**  
Turn an existing directory into a git repository  
**$ git clone [url]**  
Clone (download) a repository that already exists on GitHub, including all of the files, branches, and commits  

### Synchronize changes
**$ git fetch**  
Downloads all history from the remote tracking branches  
**$ git merge**  
Combines remote tracking branch into current local branch  
**$ git push**  
Uploads all local branch commits to GitHub  
**$ git pull**  
Updates your current local working branch with all new commits from the corresponding remote branch on GitHub. 'git pull' is a combination of 'git fetch' and 'git merge'  

### Make changes  
**$ git add [file]**  
Snapshots the file in preparation for versioning. 'git add .' stages all of your changes  
**$ git commit -m "[descriptive message]"**  
Makes commit (i.e., Records file snapshots permanently in version history)  
**$ git log**  
Lists version history for the current branch  
**$ git log --follow [file]**  
Lists version history for a file, including renames  
**$ git diff [first-branch]...[second-branch]**  
Shows content differences between two branches  
**$ git show [commit]**  
Outputs metadata and content changes of the specified commit  
