This directory has an initialized git repository. Play around here if you wish

Git Commands

git init
git clone <location> .
git commit -m ""
git pull --rebase <remoteRepoName> <branchname>
git push <remoteRepoName> <branchname>
git remote -vv
git remote add <remoteRepoName> <location>
git remote remove <remoteRepoName>
git fetch <remoteRepoName> <branchname>
git reset --hard <remoteRepoName>/<branchname>
git checkout -b <branchname>   	//create and move head to newly created branch. shorthand for git branch <branchname>; git checkout <branchname>
git checkout <branchname>	//move head to branch
git branch -vv			//find the remote branch repo that the current branch is tracking
git log
 	
