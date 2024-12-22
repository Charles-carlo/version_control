# version_control

# version-control

Explain version control:
Version control is a system that records changes to files over time, allowing you to track and manage changes, collaborate with others, and revert to previous versions of your project if needed.

Explain the difference between Git and GitHub:
Git is a version control system that runs on your local machine, enabling you to track changes, commit them, and manage branches. GitHub is a cloud-based platform that hosts Git repositories, allowing you to collaborate on projects with others, share code, and store your repositories remotely.

List 3 other GitHub alternatives:
GitLab
Bitbucket
SourceForge

Explain the difference between git fetch and git pull:
git fetch gets the latest changes from the remote repository but does not combine them into your local branch. git pull takes changes from the remote repository and automatically combines them into your local branch.

Explain in simple terms git rebase and the command for it:
Git rebase is a command used to move or combine a sequence of commits to a new base commit. It helps create a cleaner, linear project history by replaying your changes on top of the latest commit from the target branch.
        command for rebase
        git rebase <branch>

        Explain in simple terms git cherry-pick and the command for it:
Git cherry-pick is a command used to apply the changes from a specific commit (from another branch) to your current branch. It's useful when you want to apply a particular change but not all the changes from another branch.
        command for git cherry-pick
        git cherry-pick <commit-hash>
        
