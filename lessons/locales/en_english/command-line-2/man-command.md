The `man` Command
=================

Lesson Content
--------------

Gee I wish some of these programs had a manual so we can see some more information about them. Well luckily they do! Aptly named man pages, you can see the manuals for a command with the man command. 

`man ls`

Man pages are manuals that are by default built into most Linux operating systems. They provide documentation about commands and other aspects of the system. 

Try it out on a few commands to get more information about them.

`mandb`
-------

To speed up page dispatches, the `man` package maintains a database of known commands.  The problem is, you'll often be be interested in the manual pages of very recently-installed programs, which won't be in this database!  To see the manual page of a recently-installed program, you have no choice but to update the database to reflect changes in available commands.  

Enter `mandb`.

Running `mandb` explicitly requests the update of the database, so that newly-installed programs will have their manual pages available to you, the user.

Arguably, this shouldn't be a problem.  In fact, there's more than one way to solve it!  First off, it's not the 1970's, and we're not searching tape drives.  Searching directories on modern SSD's is fast.  So, you could remove this database and the problem of updating it would evanesce.  Another solution is to search the directories *after* a search of the database yields nothing, thus preserving the old functionality (speed) while implementing the new functionality (completeness).  A third solution would be to automatically run `mandb` upon the installation of new packages, which no-one seems to do.

Exercise
--------

How does the `man` command speed up page dispatches? (Hint: *Where* does the `man` package store its database?)

Question
--------

How do you update the manual pages to include very recently installed commands?

Quiz Answer
-----------

`mandb`
