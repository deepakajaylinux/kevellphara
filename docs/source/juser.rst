==============
JUser
==============

Synopsis
-------------

A user is a person who uses a computer or network service. Users generally use a system or a software product without the technical expertise required to fully understand it.

A user often has a user account and is identified to the system by a username (or user name). Other terms for username include login name, screen name.

A user's account allows a user to authenticate to a system and to be granted authorization to access resources provided by or connected to that system; however, authentication does not imply authorization. To log into an account, a user is typically required to authenticate oneself with a password or other credentials for the purposes of accounting, security, logging, and resource management.

Help Command
----------------------

This command helps to determine the usage of Juser module. The user will come to know about the different ways/format to execute this module. This command guides the end user to know the purpose of this command. Below given are the command and the screen shot of the same. 

.. code-block:: bash
        
	        jrush juser help

.. code-block:: bash

 kevells@corp:/# jrush juser help
 ****************************************
 GC JRush - The Joomla Command Line Shell
 ****************************************

  This command allows you to update JUser.

  JUser, juser

        - delete
        Deletes a user
        example: jrush juser delete

        - info
        Display the details of a user
        example: jrush juser info

        - change the password of a user
        Change a users password
        example: jrush juser password

 ------------------------------
 End Help
 ****************************************




Delete
----------------

When the user needs to delete an user in machine, the below given command will execute the process of installation.

.. code-block:: bash
        
	        jrush juser delete ..config file=”bootstrap file path”

Info
----------------

When the user needs to display the details of a user in machine, the below given command will execute the process of installation.

.. code-block:: bash
        
	        jrush juser info ..config file=”bootstrap file path”


Password
----------------

When the user needs to change the password of a user in machine, the below given command will execute the process of installation.

.. code-block:: bash
        
	        jrush juser password ..config file=”bootstrap file path”


Alternative Parameter 
-----------------------------

Either of the two alternative parameter can be used in command- juser and JUser

eg: jrush juser info ..config file=”bootstrap file path” / jrush JUser info ..config file=”bootstrap file path”                            

Benefits
--------------

* Easy to get the information about a user using a single command
* Easy to change the password of a user from back end using single command
* Easy to handle to user accounts
