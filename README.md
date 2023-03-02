# Github workshop

## Presentation:

Why Github? (store scripts and such in a place where you can keep history)

What is Github?
  * Explaining what Github is and what you can do with it in a nutshell

* Repository
  * Private
  * Public
* Issues
* PR
* Actions
* Projects
* Wiki
* Security
* Insights
* Settings (where the repo can be deleted, confirmation)

Difference between Git and Github
Github and Azure DevOps similarities/differences in a nutshell

How it works

![Emergency](img/git-workflow-steps.png)

  * Text based on [markdown language](https://www.markdownguide.org/cheat-sheet/)
  * Clone the repository
    * Start by cloning the repository to your local machine.
    * Create a new branch: Always create a new branch before starting any work.
    * Make changes: Now you can make any changes you need to make to the 'local branch' files on your laptop.
    * Stage changes: Once you have made your changes, you need to stage them. Make sure to stage all the files which are related to specific functionality, see `breaking commits`. __---- NEEDS LINK TO RELEVANT ITEM ----__

    * Commit changes: Once you have staged your changes, you can commit them in your local git clone. Remember to add a meaningful commit message that describes the changes you made.

    * Merge changes: If you are working in a team, someone else may have made changes to the same branch. In that case, you will need to merge their changes with yours before pushing.

    * Push changes: Finally, you need to push your changes to the remote repository. This makes your changes available to others, publicly of privately.


    Pull changes: Before you start working on a new feature, you should always pull the latest changes from the remote repository. You can do this using the git pull command.

These are just the basics of Git workflow, and there are many more advanced commands and techniques you can learn to make your workflow more efficient.



## Preparation (prereq):

* Create Github account
* Installation Github Desktop (Windows & Mac OS)
* Installing Visual Studio Code
* Add YAML plugin (Redhat) in Visual Studio Code
* Add indent-rainbow plugin in Visual Studio Code

## Hands-on:

* Creating new repository private
* Create README.MD with title
* Customize README.MD to sub-title
* Customize README.MD add index to sub-title
* Create feature branch
* Create PR to own main repo, explain 4 eyes principle
* Create Github action workflow with Linux and Windows VM (explain that this is an Azure VM, 2000 minutes free per month to use)
* Github action workflow add action download repository files
* Github action workflow add export to text file Linux and Windows
* Github action workflow add upload artifact
* Github action workflow add dependency build->release
* Github action workflow add pre-release



# First code of conduct:

![Emergency](img/git_emergency.png)