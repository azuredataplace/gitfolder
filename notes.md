 git config --global user.name "azuredataplace"
git config --global user.email "ericaggreydataplace@gmail.com"

git init    --- creates a git repository
git add ---  add the file so it can be given a version name
git add .  --- staged all files in the current directory
git reset ---  unstaged all files  . git reset notes.md
git log -- to see logs  
git commit -m  "message"  --- defines the version 
git remote add origin https://github.com/azuredataplace/gitfolder.git
git branch -M main
git push -u origin main