================
MysqlAdmins
================

Synopsis
---------

This module assists in installing and as well as managing the admin users for mysql without using root user. By using this, the users can manage their administrative functions.

Help Command
-------------

The Help command guides the users regarding the command used for installing the mysql admins, and also its advantages. The command used for help option under this mysql admins is shown below.

.. code-block:: bash

	cleopatra MysqlAdmins help

The screen shot as given below can lead the user in handling the help command for mysql admins.

Installation
-------------

Installing mysql admins to your machine facilitates the users to specify and manage their administrative actions. The command used for installing mysql admins is marked below.

.. code-block:: bash

	cleopatra MysqlAdmins install

In addition, the following operations shown in a tabular format occurs.

.. cssclass:: table-bordered



	+-----------------------------------+------------------------------+----------------------+-------------------------------+
	| 	Parameters	            |Alternative Parameter         | option  	          |Comments			  |
	+===================================+==============================+======================+===============================+
	|Install Admin User for MySQL? (Y/N)|In the place of MysqlAdmins   |	Y(YES)		  |If the user wish to proceed the|
	|				    |these alternative names can be|			  |installation process they 	  |
	|			       	    |used:mysql-admins, 	   |	   		  |can input as Y.                |
	|				    |mysqladmins.      	      	   |			  | 				  |
	+-----------------------------------+------------------------------+----------------------+-------------------------------+
	|Install MySQL Server? (Y/N)	    |mysql-admins,mysqladmins.	   |	N(NO)		  |If the user wish to quit the	  |
	|				    |				   |			  |installation process they 	  |
	| 			       	    |				   |	   		  |can input as N|                |
	+-----------------------------------+------------------------------+----------------------+-------------------------------+


If the user proceed the installation process, they can frame their administrative functions by specifying the following constraints.
* MySQL Root User
* MySQL Root Pass
* MySQL New Admin User
* MySQL New Admin Pass

If the user wish to process installation of mysql admins in a remote system they can specify:

* MySQL Host.

The following screenshot gives you an pictorial representation about the process of installation as described above.

Benefits
----------

* In case of mysql admins is already installed in the users machine, then an message will be appearing to inform the users as it is already installed.
* By using this module the administrators can manage their administrative actions as per the requirements.
* They can perform the installation process even in a remote system.
* Without using the root users, the users can install the mysql admins.
