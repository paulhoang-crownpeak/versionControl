This directory has an initialized git repository. Play around here if you wish

Git Commands

git init
git clone <location> .
git commit -m ""
git pull --rebase <remoteRepoName> <branchname>		//fetch from repo and branch, pull(merge) those changes into the currenct branch replay the local committed changes on top
git push <remoteRepoName> <branchname>
git remote -vv
git remote add <remoteRepoName> <location>
git remote remove <remoteRepoName>
git fetch <remoteRepoName> <branchname>
git reset --hard <remoteRepoName>/<branchname>
git checkout -b <branchname>   	//create and move head to newly created branch. shorthand for git branch <branchname>; git checkout <branchname>
git checkout <branchname>	//move head to branch
git branch -vv			//find the remote branch repo that the current branch is tracking
git branch -d <branchname>	//delete branch
git log
git reset --soft HEAD^		//undo last thing?

//change settings for the local repo...
git config user.name General-Meow
git config user.email spl.ivalis@gmail.com 	

git checkout <file>		//undo changes to a file
git merge <branchname>		//merge branchname into the current branch
git mergetool			//start the configured merge too to resolve conflicts
