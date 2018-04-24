version control = collaboration

track/revert changes

History:
1990s - CVS - Concurrent Version Systems
2000s - SVN - Apache Subversion
2005  -- Git, Mercurial (distributed version control systems)

WordPress is kept in SVN
 Version Control Types:
 Centralized Version Control (CVS, SVN)
 One central server, each client (peron) checks out and merges changes to main server

 Distributed Version Control: Git, Mercurial
 Each client (person)

 Goals of Git Design:
 Fast - add to team and code base quickly
 Each commit has a corresponding "has" track changes from everyone

 git add -A (everything in the repository)
 git add . (everything below the repository)

 gitk - graphic interface

 git checkout - like reset in SourceTree, undo local changes, goes back to last local push

 git reset HEAD hello_world.html - reset staged file
 
