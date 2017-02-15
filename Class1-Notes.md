GIT Hub

To create a repo called Sams Project on GitHub
1.	Homepage
2.	From + menu, select create a new repo in the repo name box
3.	Enter Sams Project
4.	Click add box to add a README file
5.	Click Create repo

On bottom right of screen make sure option says SSH clone URL, copy URL, go to terminaland type $git clone (paste URL).  This will create a directory with repos name.

Commit

Push to Remote(GitHub)
	$ git status – will show you what files you have changed since last commit
	$ git add (file_name_with_extension) – it’s the say cheese before you snap the photo.
	$ git commit –m “Type changes made to file” – takes the photo with a msg.
	$ git push origin master – up to Git Hub for safekeeping

Verify it on Gig Hub
	In browswer on GitHub you will see file plus the msg

Git clone- copies a remote repository and it’s files to local machine in a new directory
Git push – pushes all changes from local repo to named remote

Branching

	To make a new branch
		$ git checkout  -b new-branch-name

	branch –will list all the branches that exist in local repo

	To push this new branch to GitHub we need to clarify in the push command which branch these commits should belong to.  When you do a push always include the name of the branch that you are on locally after the origin alias.

	$ git push origin git-notes
…
To git@github.com:cewing/uge-workshop.git
*new branch      git-notes->git-notes
