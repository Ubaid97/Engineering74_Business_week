This is a guide to a secure connection between localhost and github

- create a directory using 'mkdir directoryName'
- go to the directory using cd command
- initialise a repository using 'git init'
- create a file using 'touch filename' (eg touch README.md)
- make changes to the file using 'nano filename'. save and exit using 
CTRL+X, then y
- git commit -m "commit name" 
- git branch -M main
- git remote add origin git@github.com:USER_NAME/Repo.git
- git push -u origin main
