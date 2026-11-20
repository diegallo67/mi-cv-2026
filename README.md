# CV Profesional de “Aarón > README.md
git add README.md
git commit -m Commit inicial

git branch develop
git branch release
git branch hotfixes

for rama in header menu work-experience education skills certificates languages; do
    git checkout develop
    git checkout -b 
    archivo=.md
    if [  = work-experience ]; then archivo=experience.md; fi
    echo ## Seccion  > 
    git add 
    git commit -m Agrega archivo 
done

git checkout develop
for rama in header menu work-experience education skills certificates languages; do
    git merge --no-ff  -m Integra rama en develop
done

git checkout main
git merge --no-ff develop -m Version inicial en main 


git init
git config user.name “diegallo67”
git config user.email “traviscott98@gmail.com”

git checkout -b main
echo # CV Profesional de “Aarón
