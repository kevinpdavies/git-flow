# Simple Git Flow

1. Clone a repository

    git clone https://github.com/<github-user>/<repo-name>

2. List tags of local repository

	git tag -l
	
3. Get tag of the local repository

    git name-rev --tags --name-only $(git rev-parse HEAD) 
    
4. Change local repository to a different tag if necessary

    git checkout tags/<tag_name>
    
5. Make changes to the local repository
    
6. Get status of local repository to show changed files

    git status
    
7. Add changed files to be included in the next commit

    git add <relative_path_to/file_name>
    
8. Commit these files to the local repository

    git commit  -m "Add a useful comment about the changes"
	
9. Add a tag to the local repository reflecting the committed changes

    git tag <tag_name>
	
10. Push the changes to the remote repository 
    
    git push origin <tag_name>