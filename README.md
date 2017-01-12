# phase-0-gps-1

 ls- List function. This shows all files and daughter directories within your present working directory. The user can add -a to see all files including hidden. 

rm- Remove function. Removes a file or directory within terminal. -rf will remove all sub-files and folders. 

mkdir- Make directory. This function will create a new directory within your pwd. 

cd- Change directory. This function allows the user to navigate their directories by changing to the specified location. 

git clone <url>- This function will clone a Github repo to the users local computer. It will download all files held within the github repo and establish a connection (remote tracking) that the user can push/pull from in the future. 

touch- This function is used to create files within the pwd. Any file type can be created as specified by the user. For example awesome_page.md will create a mark down file. 

git add <file name>- This function is used to place a file from the working directory into the staging area. Many file can be added at one if this is nessesary. 

git commit -m "msg"- This function is used to move the file(s) from the staging area to the git directory. This function will create a incremental log of the file that can be reverted to at any time. 

git push origin <branch>- This function will push all commits from the specifed branch to Github. Then in Github they can be properly merged and pulled back down to the local repo. 

git checkout- Can be used to move from one branch to another. If using the flag "-b" another branch can be created, while "-D" will delete the given branch.

git branch- Used to check what branch the user is currently on and what other branches exist. 

subl- Opens the given files in Sublime Text.
