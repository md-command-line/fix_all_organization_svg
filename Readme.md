## The readme is breaking <br/>Whatever automatic job is occouring on an error outputs [object Object]

1) #remove case sensitivity for bash shell we will put back in after operations.
<br/>shopt -u nocasematch 
2) search every directory for the error. and tell the directory 
`for d in ./*/ ; do (cd "$d" && cat readme.md | grep "object" && echo "$d"); done`
3) clone the 700 repositories 😰  with repo cloner.
4) run the command.
5) have the command sed fix everything.
6) run a command to fork all of them.
7) run a command to add remotes to all of them.
8) run a command to push to all the new remotes.
