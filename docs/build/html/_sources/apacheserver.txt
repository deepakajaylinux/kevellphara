==============
ApacheServer
==============

Synopsis
-----------

This modules aims at installing the Apache server. Without any request it will automatically install the current version of the apache server while installation.

Help command
-----------------

The help command describes about the purpose and the commands available under this modules. It also explains the command to install the particular module.

.. code-block:: bash

 		cleopatra ApacheServer help


The screen shot as shown below, visually represent the usage of the help command under this module.


.. code-block:: bash


 kevells@corp:/# cleopatra ApacheServer help
 ******************************


  This command is part of Core and provides you  with a method by which you can install Apache HTTP Server

  ApacheServer, apache-server, apacheserver

        - install
        Installs Apache HTTP Server
        example: cleopatra apacheserver install

 ------------------------------
 End Help
 ******************************



Installation
-------------

It is easier to install this particular tool under Cleopatra by simply using the command given below,

.. code-block:: bash

		cleopatra ApacheServer install

After giving the command above, the tool will ask as

Install Apache Server? (Y/N)

if you give an input as Y, the module will get installed successfully.

The screen shot given below explains visually about the steps and commands involves in installation.

.. code-block:: bash

 kevells@corp:/# cleopatra apacheserver install
 Install Apache Server? (Y/N) 
 Y
 *******************************
 *        Pharaoh Tools        *
 *         Apache Server!        *
 *******************************
 [Pharaoh Logging] Package apache2 from the Packager Apt is already installed, so not installing
 [Pharaoh Logging] Restarting apache2 service
 Output of config test was:
 apache2: Syntax error on line 214 of /etc/apache2/apache2.conf: Could not open configuration file /etc/apache2/httpd.conf: No such file or dir ectory
 Action 'configtest' failed.
 The Apache error log may have more information.
 * Restarting web server apache2
   ...fail!
 * The apache2 configtest failed.
 ... All done!
 *******************************
 Thanks for installing , visit www.pharaohtools.com for more
 ******************************


 Single App Installer:
 --------------------------------------------
 ApacheServer: Success
 ------------------------------
 Installer Finished
 ******************************


Options
----------

.. cssclass:: table-bordered

 +-----------------------------+-----------------------------------------+------------+--------------------------------------+
 | Parameters		       | Alternative Parameters			 | Required   | Comments			     |
 +=============================+========================+================+============+======================================+
 |Install Apache Server? (Y/N) | Instead of ApacheServer, we can use     | Yes	      | If the user gives input as yes, it   |
 |			       | apache-server, apacheserver also.       |  	      |	will proceed installation	     |
 +-----------------------------+-----------------------------------------+------------+--------------------------------------+
 |Install Apache Server? (Y/N) | Instead of ApacheServer, we can use     | No         | If the user gives input as no, it    |
 |                             | apache-server, apacheserver also.       |            | will quit the installation process|  |
 +-----------------------------+-----------------------------------------+------------+--------------------------------------+



Version
---------

While the tool is processing it will automatically grabs the most-recent updated version and makes it to get ready for installation.


Benefits to the end users
---------------------------

* This modules helps the users in installing the apache server. It simplifies the work of the users while installing the server as its 
  automatically check the current version of apache server.
* It is well-to-do in Cent OS and as well as in Ubuntu.
* The parameters used in declaration is not case sensitive, which is an added advantage.

