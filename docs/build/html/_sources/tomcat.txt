=========
Tomcat
=========


Synopsis
------------------

Tomcat is an application server from cleopatra that executes php and renders Web pages that include php coding. Tomcat is the result of developers and is available from the php Web site in both binary and source versions. Tomcat can be used as either a standalone product with its own internal Web server or together with other Web servers. Tomcat supports Ubuntu and cent OS.

Help command
------------------------

This command can function about the objectives and commands available under tomcat module. It also explains the command to install tomcat. Before installation the user read this help command.

.. code-block:: bash

		cleopatra tomcat help


The following screen shots explains its function


.. code-block:: bash

 kevells@corp:/# cleopatra Tomcat help

 ******************************


  This command allows you to update tomcat.

  Tomcat, tomcat, tom-cat

        - install
        Installs the latest version of awstats
        example: cleopatra tomcat install

 ------------------------------
 End Help
 ******************************


Installation
------------------

Use this module to install Tomcat on Ubuntu Linux systems from php. While Ubuntu includes its own Tomcat , the official Tomcat servers are generally more up-to-date. 

.. code-block:: bash

		cleopatra tomcat install

Install tomcat?(Y/N)

When the user gives input as Yes automatically it installs all depencies in default and also install updated version. The following screen shot will explain it.


.. code-block:: bash


Option
-------------

.. cssclass:: table-bordered

 +------------------------------+----------------------------------+--------------+--------------------------------------+
 | Parameters			| Alternate Parameters		   | Options	  | Comments				 |
 +==============================+==================================+==============+======================================+
 |Install tomcat(Y/N)           | Instead of using tomcat we can   | Y		  | It will install tomcat under 	 |
 |                              | use Tomcat, tom-cat		   |		  | cleopatra				 |
 +------------------------------+----------------------------------+--------------+--------------------------------------+
 |Install tomcat(Y/N)           | Instead of using tomcat we can   | N            | The system exit the installation     |
 |                              | use Tomcat, tom-cat|             |              | 		                         |
 +------------------------------+----------------------------------+--------------+--------------------------------------+


Benefits
----------------

* Its fairly extensible with modules to run things like php, python, etc. 
* It comforts with Ubuntu and cent OS. 
* Non case sensitivity is a highlighted advantage.
* Tomcat is the application layer where most of the logic processing happens. 
* Finally there would be a database layer that tomcat talks to. 
