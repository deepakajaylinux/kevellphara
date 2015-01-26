==============
Version
==============


Synopsis
-------------

This article is about the term "version" as it is used in various contexts. Software versioning is the process of assigning either unique version names or unique version numbers to unique states of computer software. Within a given version number category (major, minor), these numbers are generally assigned in increasing order and correspond to new developments in the software. At a fine-grained level, revision control is often used for keeping track of incrementally different versions of electronic information, whether or not this information is computer software.
 
Help Command
----------------------

This command helps to determine the usage of version module. The user will come to know about the different ways/format to execute this module. This command guides the end user to know the purpose of this command. Below given are the command and the screen shot of the same. 

.. code-block:: bash
        
	        jrush  version help

The pictorial representation of the help command is listed below,

.. code-block:: bash

 kevells@corp:/# jrush  version help
 ****************************************
 GC JRush - The Joomla Command Line Shell
 ****************************************

  This command Joomls Version information.

  Version, version

        - available
        Returns available Joomla Versions
        example: jrush version available

        - current
        Returns the current Joomla Version
        example: jrush version current

 ------------------------------
 End Help
 ****************************************


Available
----------------

When the user needs to know about the available joomla version, the below given command will execute the process of installation.

.. code-block:: bash
        
	        jrush version available ..config file=”bootstrap file path”


Current
----------------

When the user needs to know about the current joomla version, the below given command will execute the process of installation.

.. code-block:: bash
        
	        jrush version current ..config file=”bootstrap file path”


Alternative Parameter
----------------------------

Either of the two alternative parameter can be used in command-  jarticle, JArticle

eg:  jrush version current ..config file=”bootstrap file path”/ jrush Version current ..config file=”bootstrap file path”

Benefits
--------------

* Helps to get the information about an version in easy way
* Helps the user to get to know about the availability of the joomla version
* Helps the user to get to know about the current joomla version
