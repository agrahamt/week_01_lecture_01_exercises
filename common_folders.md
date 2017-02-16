Three Important folders

1.
Library folder
location:
/Library 
just off the main folder
"This is the top-level directory for any files that are not user data files. You typically put files in one of several standard subdirectories. iOS apps commonly use the Application Support and Caches subdirectories; however, you can create custom subdirectories.
Use the Library subdirectories for any files you don’t want exposed to the user. Your app should not use these directories for user data files." - developer.apple.com
I didn't really understand everything in this folder, but I'm a new Mac user (more experienced with Windows.  It has things that were listed as directories but which I could not go into (e.g. "cd Internet Plug-Ins" returned "no such file or directory). Other folders, such as "LaunchAgents" were merely empty.

2. 
tmp folder
Location:
/tmp
"Use this directory to write temporary files that do not need to persist between launches of your app. Your app should remove files from this directory when they are no longer needed; however, the system may purge this directory when your app is not running."
- developer.apple.com
That seems to cover it pretty well.  My tmp folder has a lot of wifi log files, comapplelnchd, and one called lwdumpoptions.   I know that Windows allows you to "cleanup" your tmp files, I wonder if it works differently for Mac.

3. Shared directory
Location:
/Users/Shared
This folder is contained alongside the directories for the various users, in my case only agrahamt and Guest.
If I want to share my files with another user of my machine, I can copy the files to the /Users/Shared folder
and other users will have access to it.  As the owner of the folder or file, I can designate it "read only" for other users.  I can also pick which users on the system can access it through permissions.
Question: Would you have to use Finder to manage permissions?
Note that by default other users are read only, they cannot edit the file unless they make it a new copy in their own user directory - or maybe even copy it within the Shared folder with a new name?
