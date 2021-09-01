# just-test-defaults

$ pwd  
/Users/william.reilly/dev/AWS/EB/tutorial/just-test-defaults

$ git remote add mygithubrepo

$ git remote -v  
mygithubrepo	git@github.com:wreilly/just-test-defaults.git (fetch)  
mygithubrepo	git@github.com:wreilly/just-test-defaults.git (push)

$ git push mygithubrepo altrestelle

(vs. "git push origin master")

-----------------------------
Toss test - master as default branch name; will try another to change that up (e.g. main or altrestelle)

And... we DID successfully change it to `altrestelle`  
cheers

https://www.git-tower.com/learn/git/faq/git-rename-master-to-main/

Local:

$ git branch -m master main << e.g.  
$ git branch -m master altrestelle << I did.

Remote:

https://www.git-tower.com/learn/git/faq/git-rename-master-to-main/github-change-default-branch.mp4

$ git push --set-upstream origin main << e.g.  
$ git push --set-upstream mygithubrepo altrestelle << I did.

$ git push origin --delete master << e.g.  
$ git push mygithubrepo --delete master << I did.


Express-generator used, with handlebars view engine. cheers aussi  
https://expressjs.com/en/starter/generator.html
