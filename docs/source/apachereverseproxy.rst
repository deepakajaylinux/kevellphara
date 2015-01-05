=============================
Apache Reverse proxy modules
=============================

Synopsis
--------

This module aims at installing the library functions. While installing the library functions, it will check the availability of already existing library functions. It helps in managing and configuring the application settings. The user can specify the default values for application settings.

Help command
~~~~~~~~~~~~~

The help command guides the user get aware of the uses, and also the options and actions that can be performed.
The coding to make use of help command under Apache Reverse proxy module, is given as follows
.. code-block:: bash
	Cleopatra ApacheReverseProxyModules help

The screen shot shown below gives you an pictorial representation of help command usage.


.. code-block:: bash

          Kevells@corp/# cleopatra ApacheReverseProxyModules help
	  ******************************


	  This command is part of Core and provides you  with a method by which you can configure Application Settings.
	  You can configure default application settings, ie: mysql admin user, host, pass

	  ApacheReverseProxyModules, apache-reverse-proxy-modules, apache-proxy-mods, apacheproxymodules, apache-lb-mods,
	  apache-load-balancer-modules

          - install
	        Installs Load Balancer/Reverse Proxy Apache Modules
        	example: cleopatra apache-lb-mods install

	  ------------------------------
          End Help
	  ****************************


Installation
~~~~~~~~~~~~~

.. cssclass:: table-bordered

	+------------------------------------------------+------------+---------------------------+
	|    Parameters	              			 | Required   | Comment  		  |
	+================================================+============+===========================+
	|Install Reverse Proxy	 	         	 |            |          		  |
	|Apache Modules (In the place of Reverse         | Yes	      | This command will install |
	|Proxy Apache Modules the user can also 	 |	      |	the apache rev proxy  	  |
	|specify the following parameters:		 |	      |	module	 		  |
	|ApacheReverseProxyModules,apache-lb-mods        |            |	         		  |
	|a pacheproxymodules ,apache-proxy-mods		 |            |		 		  |
	|apache-lb-mods,apache-load-balancer-modules     |	      |          		  |
	|apache-reverse-proxy-modules,apache-proxy-mods  | 	      |          		  | 
	+------------------------------------------------+------------+---------------------------+ 
	|Install ApacheReverseProxyModules (Y/N)	 | Y(Yes)     |If the user input as Y,the |
	|						 |            |apache reverse proxy	  | 
	|  			       			 |	      |module will be installed.  |
	+------------------------------------------------+------------+---------------------------+
	| Install ApacheReverseProxyModules (Y/N)	 | N(NO)      |If the user inputs as N,the|
	|						 |            |process will gets quit from|
	|						 |            |	installation.		  |
	+------------------------------------------------+------------+---------------------------+

While installing the Reverse Proxy Modules, it will reads the package lists, state information, builds the dependency tree. If any packages are missing, the new packages will be installed. The screenshot shown below will explains the process of installation graphically.


Benefits to the users
----------------------

It displays the available package lists, and in turn installs the missing and required packages.

The reverse proxy forwards to a fixed destination on behalf of arbitrary clients.

It will incorporates the content that is hosted from one server into a larger website.

It helps in configuring the applications settings.

