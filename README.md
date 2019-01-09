# Test

Open GitBash.
Travel in your files where you want to place the repository.
Copy the repository's link.
type: git clone repositoryLink
repositoryLink is a placeholder for the actual repository link

## Create a Branch
To create a branch, type: git checkout -b branchName
branchName is a placeholder for the actual name you want to give to you branch

## Pull from a Branch
To pull from a branch, type: git pull

## Push to a Branch
If you made any changes, type: git add fileNameWithDotExtension
fileNameWithDotExtension is a placeholder for the entire filename

To commit, type: git commit -m "the relevant message which says something should happen, not did happen"

To push to a master branch the first type, type: git push -u origin master
After that, you can just type: git push

## Merge with Master
I am interpreting this as applying changes from a branch into master. The second way described after this is a much safer practice.
Make sure you are on the master branch.
type: git merge branchName

If this is to be interpreted the other way around, which is applying changes from master into a branch, do the following.
Make sure you are on the branch you want to merge.
type: git merge master

## Fork
You need to be logged into GitHub to fork a repository on GitHub.
Get to the repository. There should be a button called "Fork" on the top right of the page. Click it.
The symbol next to "Fork" may look like what a doctor uses to check your heartbeat, but it actually represents a "fork in the road" or a split from the original source.
GitHub will have a loading page and after you're done you'll have a copy/fork of the repository.

## Add a Collaborator
You need to be logged into GitHub to add a collaborator on GitHub. The collaborator also needs to have a GitHub account.
Get to the repository. There is a button called Settings. Click it.
The sidebar on the left will will contain a Collaborators link. Click it.
To add a collaborator, you can type in their username or email in the empty text field next to the disabled Add Collaborator button.
After you type it in, the Add Collaborator button will become enabled. Click it.
