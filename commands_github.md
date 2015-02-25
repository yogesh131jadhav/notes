# Basic Commands for github

<ul>
  <li>
    * To check status of files just like which files are updated, added or commited.<br/>
    git status
  </li>
  <li>
    * To add file which is updated or added by user.
    git add <perticular file>
  </li>
  <li>
    * Commit added file (by commit we can track what we done with that commit/ which changes are we pushing to git repository)
    git commit -m”What you had changed”
  </li>
  <li>
    * Pull or push data from/to git repository
    git push origin <branch name><br/>git pull origin <branch name>
  </li>
  <li>
    * remove branch from local repository
    git branch -D <Branch Name>
  </li>
  <li>
    * We use branching strategy to keep different modules or functionality which we need to merge to combine.
    git merge --no-ff mergekaranewalibranch   (fast forward   mergekaranewalibranch means other branch rather than origional)<br/>
    ctl+o enter Override<br/>ctl+x enter Exit
  </li>
  <li>
    * to view change made by us
    git diff
  </li>
</ul>

**(We get page details for RoR)**<br/><br/>
* Check Logs <br/>tail -f log/development.log
<br/><br/>
* Install bundles<br/>
rvm gemset use mlb_app<br/>
bundle
<br/><br/>
* To precompile assets:<br/>
-pull branch<br/>
-remove assets<br/>
-commit<br/>
-Do changes<br/>
-add<br/>
-commit<br/>
-rvm gemset use mlb_app<br/>
-RAILS_ENV=staging rake assets:precompile<br/>
-Add public/assets<br/>
-commit<br/>
-push