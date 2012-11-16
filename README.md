glass-papers
============

Help with Git:

1. Configure git on your machine, adapting the following

> git config --global user.name "Alan M Turing"
> git config --global user.email amt@universal.machine

Not essential, but good practice.  It's fine to put your real name and
email address here -- I don't get any spam from doing so.

2. Set ssh keys so you can communicate securely with the server.
   See https://help.github.com/articles/generating-ssh-keys

These two steps need to be done only once per person per machine.

3. Now you can grab the files themselves:

> git clone git@github.com:jpcoles/glass-papers

4. When you add a new file:

> git add myfile

5. When you want to send your current version to the server:

> git commit -am "short message"
> git push origin master

6. To get current version from the server:

> git pull origin master

7. A useful command is

> git status

8. You can see stats and stuff here:
   https://github.com/jpcoles/glass-papers

9. Absolutely everything about git:

   http://git-scm.com/book/

