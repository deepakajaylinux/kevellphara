===========
Copy
===========

Synopsis
---------

This module handles to copy the file under Cleopatra. It has function in two ways. They are put and get. This module can work with source and destination file path. It is user friendly with Ubuntu and cent OS.  Let’s see about copy module.

Help command
--------------
             
This command can function about the objectives and commands available under copy module. It also explains the command to copy the file. Before installation you read this help command explains its function. The following image also helps you to understand this module clearly.     

.. code-block:: bash

 kevells@corp:/# cleopatra Copy help
 ******************************


  This command handles file copying functions.

  Copy, copy

        - put
        Will ask you for details for servers, then copy a file or directory from local to remote
        example: cleopatra copy put
        example: cleopatra copy put --yes --source="/tmp/file" --target="/home/user/file"

 ------------------------------
 End Help
 ******************************


Installation
--------------

It is a glaring process to copy module under Cleopatra by just using the command given below,

The main function of copy is to copy the file  from source file to destination.	Here the user has to mention the file name and destination. The following syntax is used to copy

.. code-block:: bash

  cleopatra copy put 

Example
--------
 * cleopatra copy put –yes—source=”/tmp/file”—target=”/home/user/file”

After vitalize the command it will catechize input.
The user input as yes the user has to enter as source file then it requires target file. Now the user has to enter the target file.
Finally the file has copied from source to destination. The following screenshot shows the copying of file.


.. code-block:: bash

 kevells@corp:/# cleopatra copy put
 Copy files? (Y/N) 
 Y
 /ph.php
 Enter target file path
 /home
 [Pharaoh Logging] [Copy] Executing cp -r /ph.php /home
 ******************************


 Copy Result: Success
 ------------------------------
 Copy Finished
 ******************************
 ******************************



Options
----------
The user input as copy put then access the source file path and target file path. 

.. cssclass:: table-bordered

 +-------------------------------+------------------------------+------------------------------+
 | 	Parameters	         | Directory(default)           |	Comments	       |
 +===============================+==============================+==============================+
 |put		 		 |Source to target 	        |The file path copied from     |
 |				 |	     	   	        |source to destination         |
 +-------------------------------+------------------------------+------------------------------+
 |get				 |Path to source		|Copy the files from the path  |
 |				 |			        |to source directory|          |	
 +-------------------------------+------------------------------+------------------------------+

Benefits

* The user can work with remote place also. 
* User can mention the path for source and destination. 
* It is very secure in copying. 
* Fast accessible. 
* Easily we can share the information with others. 
* The user can copy any kind of information (including sound and pictures).
* The user can copy entire file path from one folder to another.
