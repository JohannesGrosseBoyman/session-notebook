# work from the local repository to push to the remote repository
go to the local repository    
git add (file-name)     
git commit -m "a comment"     
git push origin main

# Web-Challenges Workflow
		go to the web-challenges (main)    
mkdir (folder session name e.g. css-basic)    
		navigate to the folder of step 2 (e.g. cd css-basic)        
take the git command from the challenge-handout (download all the challenges)   
		navigate back to web-challenges (main)   
git add .  - add the files   
git commit -m "Add acomment"  - create a commit   
git push origin main - push to the main branch    
		decide on which challenge you want to work   
git switch -c "challenge folder name"   
code .    
		work on the challenge and finish   
 git add .    
 git commit -m "add a comment"   
 git push origin "challenge folder name"   
 		do the pull-request on GitHub until merged    
   git switch main    
   git pull origin main 

 !!!  for the next challenge: Once Again (git switch -c "challenge folder name")    

# For every challenge in your folder (web-challenges) use these git commands:
git add (challenge folder name)  
git commit -m "message"   
git push  

# Initialize a folder on your GIT as local repository
git init   
git status   

# check the connecting of the local repository to GitHub repository
git remote -v  

# Committing in a local repository:
git status   
git add (filename)    
or (git add -all)    
git commit -m "addfoo"    

# Cloning a remote repository
git clone https://github.com/JohannesGrosseBoyman/session-notebook.git (this is the SSH Link of the remote repository)

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
git branch -d (branchname)  - delete a branch   

# to link your local Git repository to a new remote repository   
git remote add origin (SSH-link)     
git branch -M main   
git push -u origin main    

