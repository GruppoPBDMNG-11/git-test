//COMANDI GIT

git clone /percorso/del/repository

git nano <nomedelfile>

git add <nomedelfile>

git commit -m "Messaggio per la commit"

git push origin master

//Add tag:
git tag 1.0.0 <id del commit>

//Carica il tag sul server:
git push origin <tagname>

//Rimpiazza ciò che è nella HEAD:
git checkout -- <nomefile>

//Remove remote branch: 
git push origin :the-remote-branch

//Merge branch
git checkout master
git pull origin master
git merge primobranch
git push origin master

