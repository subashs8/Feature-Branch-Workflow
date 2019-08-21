# Feature-Branch-Workflow
Team Names: Subash Shibu, Keagan Wilson, Alan Liang, Yoga Kanneboina

Name of Workflow: Feature Branch Workflow

Description of Basic Workflow: 
In the basic workflow, a team will have a common version of the code or project. Then, the each member of the team will make a clone of the copy of the original program and make their own edits. Once they are done with their edits to the program, they will push their code to their local workspace and then to the group's workspace. A problem that may arise is that a member of the team might not be able to push their code to the master branch if there are too many changes to the original code. In order to solve this problem, each team member must update their code with the recent changes that were commited. 

Description of Feature Branch Workflow:
In the feature branch workflow, instead of immediately committing the changes to the master branch, the team will agree that they should commit changes to a seperate branch first. One advantage of this is that there will be less errors in the master branch code. In this way, the designated primary commit branch and the master branch act together as a version control system. It also lets the team members preview a feature before commiting to the master branch. When using this technique, team members name the different branch descriptively so that they describe a specific feature that they are working on. The idea behind the Feature Branch Workflow is that it is a versatile workflow that allows multiple developers to work on the project without disturbing the main codebase.

Key Differences from basic workflow, and key use cases 

Link to your Git example repository: https://github.com/subashs8/Feature-Branch-Workflow

Diagram or Diagrams of workflow:
https://github.com/subashs8/Feature-Branch-Workflow/issues/url


Documentation of git commands used, and annotated sample sequence of commands used in creating your repository
$git clone https://github.com/subashs8/Feature-Branch-Workflow
Clones the branches in the repository
$git cd master
$git checkout master 
Updates the master branch with existing changes
$git fetch origin
Reads the code in the origin file
$git reset --hard/origin master
Makes sure the origin branch is the same as the master branch 
$git checkout -b new-feature 
Creates a branch with the new feature’s name
$git status
Shows what updates have been made
$git add new file
Adds a new file
$git commit 
Commits the edits
$git push -u origin new feature
Pushes the feature to a backup branch 
