BorgHammer
==========

For both hosts and participants, a lot of times doing an Android based code-lab or workshop feels like being given a box of screws and a hammer, and being told 'get to work'. One of the major problems is that getting the Android development environment set up initially is not trivial, and fairly error-prone. As a result, many times workshops end up being mostly about setting up development environments, and very little about actually building stuff. 

This project provides a VirtualBox image, along with instructions, that can be distributed on a flash drive, with everything set up and ready to go. 

* Download the image from here: <not quite ready yet!>
* Verify the MD5 sum: ---
* Extract the archive, then import the .ova file into VirtualBox 4.3
* Fire it up
* Credentials are dev/dev (user/pass)

A few notes:

* You must be running on an x86_64 host.
* SDK and Studio are installed in ~/bin/
* Code lives in ~/workspace/
* Many Glass samples have been pulled down, and imported into AS
* There should be NO EMULATORS (obvious performance issues)
* Other things installed:
** Emacs
** Maven
** Vim
** Java 7
** Android Studio 1.0 RC1
