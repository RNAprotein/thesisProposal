thesisProposal
==============

This folder is to keep the most up-to-date files of thesis proposal, and commit to github for better version control.

Thus, only the essential files are kept. That means, basically, only these files are stored and updated here:
1. tex 
2. bib
3. files for figures
4. pdf
5. files for templates

There are normally two branches in this git folder:

1. master: the one that keeps the most recent **FINALIZED** version of files
2. updates: the one that used to make updates and comparisons, like a working/developping branch

So all the new things come to "updates" branch first, merge the branch in "master" branch, then use diff to compare if there is any conflicts, then push to github. "master" branch stores only those most stable version.

Some initialization work:

1. shortcut for url (or local path): git remote add <name> <url>
> git remote add thespro https://github.com/syang11/thesisProposal.git
2. .gitignore file
