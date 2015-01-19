==============
Chown
==============

Synopsis
----------

This module enables to change owner’s permission. It change the permission on individual file 
Or directory. Before that you must be aware of the default permission assigned to your files and directories at the time you create it. 

Help command
--------------

This help command explains about the installation of a particular module. The help command is easy to operate by the end user. The following command guided the user about the installation.

.. code-block:: bash
	
	cleopatra chown help

After giving the command, the command will list the help options. The following screen shots will give visual effect for the usage of this module.

.. code-block:: bash

	Kevells@corp:/# cleopatra chown help
	******************************

	 This command handles file user ownership changing functions.

	  Chown, chown

        - path
        Will change the user ownership of a path
        example: cleopatra chown path --yes --guess --recursive --path=/a/file/path --owner=golden

	------------------------------
	End Help
	******************************


Installation
--------------

It is an excellent process for this module under Cleopatra by slightly using the command given below,

.. code-block:: bash

	Cleopatra chown path –yes—guess—recursive—path=/Cleopatra—owner=Kevells

Then we can enter the input.
Enter Ownership User
After typing the owner name
It will display Chown result success.
This will visually shows by the following screen shot.

.. code-block:: bash

	kevells@corp:/# cleopatra chown path --yes --guess --recursive --path=/phj.php --owner=deepak

	Enter ownership user:
	deepak
	[Pharaoh Logging] [Chown] Executing chown -R deepak /phj.php
	******************************


	Chown Result: Success
	------------------------------
	Chown Finished
	******************************




Benefits to the users
----------------------
The module can change the owner at any time with Cleopatra. While doing recursive process if you change single file the entire folder can also be changed. We can verify the current status of the owner.



Options
---------

.. cssclass:: table-bordered


	+------------------------------------------------+------------+----------------------------+-----------------------------+
	| 	Parameters	              		 | Required   | option  		   |Comments			 |
	+================================================+============+============================+=============================+
	|Chown	 			 		 | Yes	      |	__			   |				 |
	+------------------------------------------------+------------+----------------------------+-----------------------------+
	|Path						 | Yes	      |	__			   |The user has to give the     |
	|						 |            |			           |path			 |
	+------------------------------------------------+------------+----------------------------+-----------------------------+
	|Owner				 		 | Yes        |	Chown       		   |				 |
	+------------------------------------------------+------------+----------------------------+-----------------------------+
	|Owner						 | No         |	Chown			   |The user gives input as no,	 |
	|                                                |	      |				   |it will ask the owner name|  |
	+------------------------------------------------+------------+----------------------------+-----------------------------+

