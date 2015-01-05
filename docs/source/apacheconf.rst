ApacheConf
=============

Synopsis
--------

This module assists in managing and installing the Apache configuration. It specifies the configuration of your environment. It is well-to-do in ubuntu and as well as in Cent OS.

Installation
-------------

It is easier to install this particular tool under Cleopatra by simply using the command given below,

.. code-block:: bash
 
 cleopatra apacheconf install

After giving the command above, the tool will ask as

.. code-block:: bash

  Install Apache conf? (Y/N)

if you give an input as Y, the module will get installed successfully.
It will also throw some commands to specify the non-default values for LockFile, PidFile, Timeout, KeepAlive, MaxKeepAliveRequest, KeepAliveTimeout. If the user gives input as Y(Yes) it will automatically fix the default value. If the user gives input as N(No) then it will enquire about the values from the user.

The screen shot given below explains visually about the steps and commands involves in installation.

Options
********

.. cssclass:: table-bordered

	+------------------------------------------------+------------+----------------------------+
	| Parameters	                                 | Required   |Comment  		   |
	+================================================+============+============================+
	|Install                               		 | Y(YES)     |It will install the         |
	|              					 | 	      |apacheconf under            | 
	|	                                         |            |Cleopatra		   |
	+------------------------------------------------+------------+----------------------------+ 
	| Install Apache conf? (Y/N)		         | Y(YES)     |If the user gives input as  |
	|	                               		 |            |yes, it will install        | 
	|                                  	         |	      |the module.                 |
	|	                              		 |            |		              	   | 
	+------------------------------------------------+------------+----------------------------+
	| Install Apache conf? (Y/N) 	                 | N(NO)      |If the user gives input 	   |
	|	                                 	 |            |as no, it will get	   |
	|                                         	 |            |exit.|
	+------------------------------------------------+------------+----------------------------+


Benefits to the users
----------------------

The module assists the end user in installing and managing the configuration of Apache. While installing the Apache tool, the end user can design and manage the configuration as per their requirement using this module. If it founds the configuration already exists it will overwrite the existing one.

Help command
-------------

The help command describes about the purpose and the commands available under this modules. It also explains the command to install the particular module.
The screen shot as shown below, visually represent the usage of the help command under this module.

