The head is a pointer indicating what branch you are currently on.  To switch from a Master branch to a Test branch,
you would type "git checkout test.'  Then your head would be on the test branch.  
If you made some changes on the test branch and committed them, it would have diverged from the Master branch, and because
you see whatever is checked out (whatever is the "head" branch), the files you see would match that branch.
If you checkout the master again, it is now the head branch and doesn't show the test changes.  the two branches have
diverged.  I can now make edits in the master branch starting at the point before new edits were made to test.  Later, I can merge the two branches and will have to use diffs to determine what edits I want to keep as I combine the two branches of edits.  The test branch may still exist afterward but until new changes are made it will be identical to the master branch.
