=============
NetworkTools
=============

Synopsis
----------

The network tools are software utilities designed to analyze and configure various aspects of computer network. The most common network tools found on most operating system includes Traceroute , Netstat and Ping. Each network tools have its own functions.

For example: 

Ping is used to check connectivity

Netstat is used to display network connection both incoming and outgoing

Help Command
--------------

This command helps to determine the usage of network tools module. The user will come to know about the different ways/format to execute this module. This command will guide the end user to know when and how the command to be used. Below given are the command and the screenshot of the same. 


.. code-block:: bash

		cleopatra networktools help


The pictorial representation of the above command is listed below,


.. code-block:: bash

 kevell@corp:/# cleopatra NetworkTools help
 ******************************


  This command allows you to install a set of common Network Tools. These include
  traceroute, netstat, lsof, telnet and ps.

  NetworkTools, networktools, network-tools

        - install
        Installs the latest version of Network Tools
        example: cleopatra networktools install

 ------------------------------
 End Help
 ******************************


Installation
---------------

When the user needs to install any network tool in machine. The below given command will execute the process of installation.

.. code-block:: bash


 	cleopatra networktool install



.. cssclass:: table-bordered

 +-----------------------------+--------------------------------+-------------------+-------------------------------------+
 | Parameters		       | Alternative Parameters		| Options	    | Comments				  |
 +=============================+================================+===================+=====================================+
 |Cleopatra Networktools       | NetworkTools, networktools,    | Y		    | System starts installing the 	  |
 |Install		       | network-tools			| 		    | network-tools			  |
 +-----------------------------+--------------------------------+-------------------+-------------------------------------+
 |Cleopatra Networktools       | NetworkTools, networktools,    | Y                 | System stops installing function    |
 |Install                      | network-tools|                 |                   | 		                          |
 +-----------------------------+--------------------------------+-------------------+-------------------------------------+



Once the installation command executed, the system ask for the confirmation by yes/no "Y/N" question. Once the confirmation given from our end, the system starts executing the function and the system ends up with the final result. Below given is the screenshot for the same.


Benefits
-----------

This module helps in installing the set of common network tools. This benefits the users to install various tools which can be useful when networking with other computers both within the network and across the internet. This helps the users who are working with remote machines.
