EXPLAIN VERSION CONTROL
Version control, also known as source control or revision control, is a system that manages changes to a project's files over time. It enables multiple people to work on a project simultaneously, keeping track of modifications and facilitating collaboration.

DIFFERENCE BETWEEN GIT AND GITHUB
Git is a distributed version control system (DVCS) for tracking changes in source code. Operates locally on a developer's machine while GitHub is a web-based platform that uses Git for version control. Provides a central hub for hosting, collaborating, and managing Git repositories with additional collaboration features.

3 OTHER GITHUB ALTERNATIVES
1. GitLab
2. Bitbucket
3. SourceForge

DIFFERENCE BETWEEN GIT FETCH AND GIT PULL
In Git, git fetch and git pull are both commands used to update a local repository with changes from a remote repository, but they operate differently. 
git fetch retrieves changes from the remote repository, including new branches and updates to existing branches, but it doesn't automatically merge the changes into the local working branch. It allows you to inspect and review the changes before deciding to merge. 
On the other hand, git pull not only fetches the changes from the remote repository but also automatically merges them into the current working branch. 

DIFFERENCE BETWEEN GIT REBASE AND THE COMMAND FOR IT 
git rebase is a Git command used to integrate changes from one branch into another by moving or combining commits. Unlike merging, rebase modifies the commit history by applying each commit in the specified branch individually on top of the target branch. This results in a linear and cleaner history. The command for git rebase is "git rebase <target_branch>". For example, to rebase the current branch onto the main branch, you would use "git rebase main".

GIT CHERRY-PICK AND THE COMMAND FOR IT
git cherry-pick is a Git command used to apply a specific commit from one branch to another. It allows you to choose and pick individual commits and apply them to the current branch, essentially replicating changes without merging entire branches. The command for git cherry-pick is "git cherry-pick <commit_hash>", where "<commit_hash>" is the identifier of the commit you want to apply. 