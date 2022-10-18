# git-template
### first commit empty  
git init  
git commit -m "first commit" --allow-empty  
git remote add origin https://github.com/muser../rep..o.git  
git branch -M main  
git push -u origin main  

### branch create checkout  
git checkout -b dev  
git rm --cached -r  
git commit -m "dev first commit" --allow-empty  
git push -u origin dev  

git add .  
git commit -m "dev"
git push -u origin dev  

### delete branch local and remote
git checkout main  
git branch -D dev  
git push origin --delete dev  

### git push 取り消し
git reset --hard HEAD^  
git push -f origin HEAD  

### git add 取り消し
git rm --cached -r .  

### git status
git status  
