Three step process for managing files in Git.
1. Modify - 
this just means working on the files themselves, say by using touch (not a git command, to create a text file in the initialized folder and editing it in nano.
There really aren't any relevant git-specific commands for this stage.

2. Stage - 
So far we have learned that when we use the "git add" command on a file or files (or all), we are telling git that we intend
to commit the current version of that file.  This staging process (the stage is also called the index) stores the specific version of the file at that exact point. It does not commit them.  Also, if you make any new changes to a file AFTER adding it, and then commmit, those post-add changes will not be committed.  This is why its important to add right before committing and not make any changes between the two processes.
Is this right?  Or do the later changes actually get committed?

3. Commit - 
"Once you have added files to the staging area you can commit them. When you commit, 
you are instructing Git to record the files in the staging area into a record in the repository history."  
I still don't fully understand what the staging "add" does that is separate from the commit.  It seems like a stop-gap measure, 
by which I mean it forces us to think "are you sure?"
