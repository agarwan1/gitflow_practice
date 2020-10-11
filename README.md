# gitflow_practice <br />
git clone --recursive git@github.com:<agarwan1>/gitflow.git <br />
git flow init <br />
git flow feature start 112 <br />
vi test.txt <br />
git add . <br />
git commit -a <br />
git push --set-upstream origin feature/112 <br />
git flow feature finish  <br />
git push --set-upstream origin develop <br />
git flow release start 1.0.1 <br />
git add . <br />
git commit -a <br />
git flow release finish <br />
git checkout main <br />
git push origin --all--follow-tags 
