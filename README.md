git config --global user.name "Lissette"  
git config --global user.email carballolissette30@gmail.com
git init 
git branch -m main 
git status    
git add .
git commit -m "Estructura inicial del proyecto"
git log --oneline
git checkout -b desarrollo
git branch
git diff
git add .
git commit -m "Agregar contenido en el index" 
git log --oneline
git checkout main
git merge desarrollo
git diff
git add .
git commit -m "Cambio temporal"
git reset --soft HEAD~1
git log --oneline
git commit -m "Cambio temporal"
touch .gitignore
New-Item .gitignore
git add .
git commit -m "Agrega gitignore"
git log --oneline
git remote add origin https://github.com/LisCarballo27/Laboratorio-git.git
git push -u origin main 
git push -u origin main --force
git checkout -b login
New-Item .login.html
git add .
git commit -m "Agrega login"
git push origin login
git add .
git commit -m "Actualizacion2 login"
git add .
git commit -m "Actualizacion2 login"
git push origin login 
