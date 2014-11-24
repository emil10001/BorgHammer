BorgHammer
==========

What is this?

Running Android (or Android based) code labs, and dealing with the issue of setting up new users is currently really painful. This is something that I've run into time and time again, and it ends up typically chewing through the entire workshop. This project provides a VirtualBox image, along with instructions, that can be distributed on a flash drive, with everything set up and ready to go. 

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
