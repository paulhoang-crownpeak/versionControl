#Mercurial commands

- hg init
- hg clone \<remoteLocation\>
- hg add
- hg commit -m 'blah'
- hg pull
- hg push
- hg up -r \<rxxx\>
- hg up
- hg merge \<branchToMergeIn\>
- hg merge //merge tips of the current branch
- hg branch \<branchName\>
- hg co -r -C .
- hg rollback
- hg graft -r \<rev\>
- hg tag \<myTagName\>
- hg tag -l


### in hgrc
[main]

default = https://hgrepo/reponame

myfork = https://anotherRepo/reponame
