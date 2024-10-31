# For every challenge in your folder <web-challenges> use these git commands:
git add <challenge folder name>
git commit -m "message"
git push

# Initialize a folder on your GIT as local repository
git init
git status

# check the connecting of the local repository to GitHub repository
git remote -v

# Committing in a local repository:
git status
git add <filename>
or (git add -all)
git commit -m "addfoo"

# Cloning a remote repository
git clone https://github.com/JohannesGrosseBoyman/session-notebook.git (this is the url of the remote repository)

# in the local repository: Create a new branch in the VS terminal: (Esraa)
enter your code in VS
go to Prettier – then Terminal
  git pull origin main
  git switch -c feature/change-message
  git status
  git add . 
  git status
  git commit -m „message update“
  git push origin feature/change-message

continue on GitHub:
	open Pull Request
	create Pull Request (at this point revisors need to agree)
	Merge

again on the local repository folder/terminal:
	git switch main
	git pull origin main

	delete the new branch on GitHub and locally
git branch -d <branchname>  - delete a branch
 


