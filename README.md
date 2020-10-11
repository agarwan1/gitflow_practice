# gitflow_practice
git clone --recursive git@github.com:<agarwan1>/gitflow.git
git flow init
git flow feature start 112
vi test.txt
git add .
git commit -a
git push --set-upstream origin feature/112
git flow feature finish 
git push --set-upstream origin develop
git flow release start 1.0.1
git add .
git commit 0a 
git flow release finish
git checkout main
git push origin --all--follow-tags
