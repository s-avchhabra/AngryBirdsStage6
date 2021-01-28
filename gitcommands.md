#Git Commands
## Configuration
git config --global user.email "youremail@xyz.com"
git config --global user.name "yourusername"

## General commands
pwd - present working directory
ls - list down all the files and folders
cd - change a directory
mkdir - make a new directory

## Cloning a repository & uploading back remotely
- Open the repository to clone and copy URL.
- git clone PASTEURL
- ls 
- cd newfoldername
- Minimize the terminal and continue coding
- Post the coding, open the terminal
- git status (to check for new, modified or deleted files)
- git add filename (to add modified or new files)
- git commit -m "changes you have made"
- Open github profile. Create a new repository and copy URL.
- git remote add remotename PASTEURL
- git push -u remotename 
- git log (check the changes made to the repository by multiple users)