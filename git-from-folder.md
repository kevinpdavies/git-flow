# Add an existing folder as a new Github repository

1. Create the new repository on Github. Choose whether to create a README (easier not to but if created then see step 6). Copy the repository URL to the clipboard.

2. Go to the local folder and initialise as a git repository:

	git init
	
3. Add all the existing files to the local repository:

    git add . 
    
4. Commit the existing files with a comment:

    git commit -m "Initial commit"
    
5. Connect the local repository to the remote repository URL (from Step 1):

	git remote add origin https://github/username/reponame.git
	
	git remote -v
    
6. If a README file was created in step 1 then pull this to the local repository:

    git pull origin master
    
7. Push the files to the remote repository:

    git push origin master
    