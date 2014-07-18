IntroToGit
==========

A Brief Introduction to Git(ABC hackathon)

What the hack is Git(hub)?

Git is a source code management tool that allows you to manage your project repository, control its versions and collaborate with others.

** Let's start by setting up. **

1.1 Sign up at https://github.com/

1.2 Set up Git
	Follow the intructions at https://help.github.com/articles/set-up-git

** Now let's download this repo to your local computer and run the magic! **

2.1 "Fork" it:
Press the "Fork" button at the top right corner of this page (https://github.com/nonlocalStream/IntroToGit)
(To Fork is to copy other user's repo to your own account. It easier to make changes to repos on your own account.)

2.2 "Clone" it:
Go to your repo. Copy the url.
In terminal, navigate to the folder you want to download and run:

	$ git clone (the url you copied)

For example in my case, it's:

	$ git clone https://github.com/nonlocalStream/IntroToGit

2.3 Change its "status":
Open warmup.txt in your local repo. Fill out the quiz.
Check the status of git by running this in your repo:

	$ git status

2.4 "Add" it:
As the result of "git status" tell you, "add" the file to prepare for a commit.
Run:

	$ git add warmup.txt

or

	$ git add -A (which add all files modified)

2.5 "Commit" the change:
Run:

	$ git commit -m "What ever you want to say in this commit"

(A commit is the change that you'll upload to remote repo. It's like a package. You "add" file to the package and send the package to the remote end)

2.6 "Push" the change:(aka. send the package)
Run:

	$ git push origin master

(Before, we only record the changes in our local computer. "Push" enables us to update the repo remotely on GitHub)
(A figure about the relationship between add, commit and push)

** Pair with the person(people) next to you and work as a team. **

3.1 Add teammate's repo collaboraters:

3.2 Clone your teammate's repo.
(Notice: Don't fork this time cuz you want to makes changes to your teammate's repo not your own's)
(Notice2: make sure you have your own repo and your teammate's repo in different folders)

3.2 Add, commit, push to your teammate's repo:
Navigate to the new repo, in the "teammate" folder add a new file which is named after your own name. (Put whatever you want inside it) Add it, commit it and push it.

3.3 "Pull" it:
Now if you go to your own remote repo on website. You should see your teammate's commit. However, you haven't update your local repo yet.
Navigate to YOUR OWN repo, run:

	$ git pull

After a while, you can see your teammate's name inside "teammate" folder

** Others and Resources: **

diff, branch, checkout, merge, stash, ...
