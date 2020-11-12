## How to use  the cookie cutter
execute:
cookiecutter.exe osprojecttemplate

make repo on github  "<Repo Name>"

go to the new directory and execute: 
git init
git add .
git commit -m 'first commit'

git remote add origin https://github.com/<your githubpage>/<Repo Name>.git
git branch -M main
git push

### Set Up IO
go to: 
https://github.com/<your githubpage>/<Repo Name>/settings
and select the branch "gh-pages" and dir "root" 