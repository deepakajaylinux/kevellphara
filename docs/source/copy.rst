=====
Copy
=====

Synopsis
--------

This modules assits to copy the file under Cleopatra. It has function in two ways. They are put and get. This module can work with source and destination file path. It is user friendly with Ubuntu and cent OS.  Let’s see about copy module.

Help command
-------------
     
This help option depicts the objectives and commands available under copy module. It also explains the command to copy the file along with the syntax in two different ways. Before installation the user can read this help to know about its function. The following command and image helps you to understand this module clearly.     


.. code-block:: bash

	cleopatra copy help

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


How to Use
----------

It is a glaring process to use this copy module under Cleopatra by just using the command given below,

The main function of copy is to copy the file from source file to destination. Here the user has to mention the file name and destination. The following syntax is used to copy

.. code-block:: bash

  cleopatra copy put 

Example
-------

.. code-block:: bash
  
 cleopatra copy put –yes—source=”/tmp/file”—target=”/home/user/file”

After inputting the command above, the user has to input as yes for copying the files, after that the user has to specify the location of source and destination file.
Finally the file will get copied from source to destination. The following screenshot shows the copying of file.


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



.. cssclass:: table-bordered

 	 +-------------------------------+------------------------------+------------------------------+
	 |  Parameters                   | Directory(default)           | Comments                     |
 	 +===============================+==============================+==============================+
	 |put                            |from source to destination    |			       |
             								|The place the file from       |
	 |                               |                              | source to destination        |
	 +-------------------------------+------------------------------+------------------------------+
	 |get                            |from destination to source    |Copy the files from the       |
	 |                               |                              |to source directory	       |
	 +-------------------------------+------------------------------+------------------------------+



Benefits
--------

* The user can work with remote place also. 
* User can mention the path for source and destination. 
* It is very secure in copying. 
* Fast accessible. 
* Easily we can share the information with others. 
* The user can copy any kind of information (including sound and pictures).
* The user can copy entire file path from one folder to another.
