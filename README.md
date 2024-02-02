# A02
IS117Section004
Jake DeMonaco

<!-- Define Terms -->
Branch - A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master . As you start making commits,   you're given a master branch that points to the last commit you made.

Clone - git clone is a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository.

Commit - Commits can be thought of as snapshots or milestones along the timeline of a Git project. Commits are created with the git commit command to capture the state of a project at that point in time. Git Snapshots are always committed to the local repository.

Fetch - The git fetch command downloads commits, files, and refs from a remote repository into your local repo. Fetching is what you do when you want to see what everybody else has been working on. 

GIT - Git is a version control system used for tracking changes in computer files. It is generally used for source code management in software development. Git is used to tracking changes in the source code. The distributed version control tool is used for source code management.

Github - GitHub is a web-based version control and collaboration platform for software developers.

Merge - Merging is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch. Note that all of the commands presented below merge into the current branch.

Merge Conflict - Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge.

Push - The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo.

Pull - The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. Merging remote upstream changes into your local repository is a common task in Git-based collaboration work flows.

Remote - A remote URL is Git's fancy way of saying "the place where your code is stored." That URL could be your repository on GitHub, or another user's fork, or even on a completely different server.

Repository - A Git repository is a central storage location for managing and tracking changes in files and directories. It is a crucial component of the Git version control system, which enables collaborative development and allows multiple developers to work on a project simultaneously.

<!-- Setting up github with a connection to git through your terminal -->

1. The first step to creating a github account is simple, you need to go to github.com and create an account and sign up with your email
2. The next step is to install git bash on your computer (this will act as an upgraded terminal)
    https://www.educative.io/answers/how-to-install-git-bash-in-windows
    https://github.com/git-guides/install-git    
3. Next you will need to connect your git bash to your github.com account so you can seamlessly add, commit, and push your changes to your documents up the live internet.
https://medium.com/@rahulsharan512/how-to-connect-git-bash-to-your-github-account-two-easy-methods-a332e037dea5
4. You will need to also set up something called SSH keys to be able to establish a connection between your machine and github.
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account
5. At this point, you will want to navigate to github.com and create a new repository for whatever you want to work on. (A tip is to check the box to include a README.md file to get something in your repository.)
https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository
6. The next thing I would do is naviage to your repository on Github.com and on the tabs at the top naviage to Settings.  After that, go to the Pages tab.  Here you can set your Github repository to a live page hosted by github!  All you have to do is go to the branch section, and set the source as Main, and then click save!  Now your github repo will be hosted online.
7. The next step is cloning this repository you just made to your local machine so you can establish the connections between the files, and edit them! You're going to copy the link to your repository from the green CODE button, then copy the link to the clipboard from the HTTPS section.  You then type the command "git clone link" and replace link with the one you copied from your github repo.  NOTE: whatever folder you're in is where the repository will live on your local machine, and you need to be inside the master folder of that repository to (add, commit, and push) information in that order.
https://blog.hubspot.com/website/clone-github-repository
8. At this point make changes to your project inside the repository folder, and then when you are satisfied in the git bash window type "git add ." this will add all the changes you've made.  Then, git commit -m "type a comment here" this readies the changes to go to your repository on github.  Inside the quotation marks supply a comment on what happening for organization purposes.  Lastly, type "git push origin main" This is the command that finalizes everything and pushes your changes up to github on the main branch!
9. If you are working with multiple branches you will need to push to "git push origin otherbranch" then you can merge the working branch into the main branch on github.com
10. Any changes that may have been made to your github repository on Github.com can be resynched up to your account by running the command "git pull origin main" in your gitbash.