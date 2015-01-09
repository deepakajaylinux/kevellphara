============
Sudonopass
=============



Synopsis 
---------------

Sudonopass used to run a particular command with root permissions. The interesting thing is that when the user use sudo for a particular command, system prompts the user for current user’s password. Once the user enter the password, the command runs with root privileges. This is suitable to work with Ubuntu and Cent OS.

Help command
-----------------------

This help command guide the user about sudonopass module. This is suitable for all type of business users. The help command shows a short list of the commands built into the sudonopass module. The following screen shot enumerate it.

Installation
------------------

Use this module to install sudonopass on Ubuntu Linux system packages. 

.. code-block:: bash

          Cleopatra sudonopass install

Install sudonopass ?(Y/N)

When the user gives input, as yes automatically it will install configure the root pass access for everybody. The following screen shot will explain it.

Option
------------
.. cssclass:: table-border








+===============+=======================+===========================================+
| Parameters           |            Dirctory(default)        |                      Output                                                           |
+===============+=======================+===========================================+
| Install sudonopass |     	yes		  |       It will install    sudonopass under Cleopatra           |                                                                                                          
|                                   |                                                 |                                                                                           +================+=======================+==========================================+                  
| Install sudonopass  |                   No                         |                          It will exit                                                   |                |
+================+=======================+==========================================+


Benefits
Sudonopass makes sure that root privileges are there for a specific command (or for a specific time) and not for the complete session as that may result in accidental misuse of root privileges.
 The user can use sudonopass even grant limited privileges to a user. This is helpful when the user do not want a user to have control of all the root powers while doing a sudonopass.
The best advantage is that sudonopass requires user’s own login password rather than root password. This helps in keeping root password private and there is no need to change it even when a user (sudoer) leaves.
This file provides information on the commands that were execute using sudo and their time of execution. This helps administrator to keep track of even trusted users

