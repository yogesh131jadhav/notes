# Basic Commands for github

* To check status of files just like which files are updated, added or commited.

git status


* To add file which is updated or added by user.

git add <perticular file>


* Commit added file (by commit we can track what we done with that commit/ which changes are we pushing to git repository)

git commit -m”What you had changed”


* Pull or push data from/to git repository

git push origin <branch name>

git pull origin <branch name>


* remove branch from local repository

git branch -D <Branch Name>


* We use branching strategy to keep different modules or functionality which we need to merge to combine.

git merge --no-ff mergekaranewalibranch   (fast forward   mergekaranewalibranch means other branch rather than origional)

ctl+o enter Override

ctl+x enter Exit


* to view change made by us

git diff


**(We get page details for RoR)**

* Check Logs 

tail -f log/development.log


* Install bundles

rvm gemset use mlb_app

bundle


* To precompile assets:<br/>

-pull branch

-remove assets

-commit

-Do changes

-add

-commit

-rvm gemset use mlb_app

-RAILS_ENV=staging rake assets:precompile

-Add public/assets

-commit

-push