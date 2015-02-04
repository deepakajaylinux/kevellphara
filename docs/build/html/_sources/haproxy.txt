===========
HAProxy
===========


Synopsis
-------------

HAProxy is a free, open source high availability solution, providing load balancing and proxy for TCP and HTTP-based applications by spreading requests across multiple servers. Has a reputation for being fast and efficient (in terms of processor and memory usage).

Help Command
----------------------

This command helps to determine the usage of HAProxy module. The user will come to know about the different ways/format to execute this module. This command will guide the end user to know when and how the command to be used. Below given are the command and the screenshot of the same. 

.. code-block:: bash
        
	        cleopatra HAproxy help


The pictorial representation of the above command is listed below,

.. code-block:: bash


 kevell@corp:/# cleopatra HAProxy help

 ******************************


  This module provides installs HA Proxy Server

  HAProxy, ha-proxy, haproxy

        - install
        Installs HA Proxy Server
        example: cleopatra haproxy install

        - configure
        Configure Load Balancing with HA Proxy Server
        example: cleopatra haproxy configure

 ------------------------------
 End Help
 ******************************


Installation
----------------

We can install HAProxy using distribution's package manager. When the user needs to install HAproxy module in machine. The below given command will execute the process of installation.

.. code-block:: bash
        
	        cleopatra HAproxy install

The pictorial representation of the above command is listed below,


.. code-block:: bash

 kevell@corp:/# cleopatra haproxy configure

 *******************************
 *        Pharaoh Tools        *
 *         HA Proxy Server!        *
 *******************************
 
 What is the environment name you want to balance load to? 
 
 PHP Notice:  Undefined index:  in /opt/cleopatra/cleopatra/src/Modules/HAProxy/Model/HAProxyConfigureUbuntu.php on line 102
 PHP Notice:  Undefined index:  in /opt/cleopatra/cleopatra/src/Modules/HAProxy/Model/HAProxyConfigureUbuntu.php on line 102
 PHP Warning:  Invalid argument supplied for foreach() in /opt/cleopatra/cleopatra/src/Modules/HAProxy/Model/HAProxyConfigureUbuntu.php on line 75
 Set non-default value for global_log? Default is 127.0.0.1 local0 notice (Y/N) 

 Set non-default value for global_maxconn? Default is 20000 (Y/N) 

 Set non-default value for global_user? Default is haproxy (Y/N) 

 Set non-default value for global_group? Default is haproxy (Y/N) 

 Set non-default value for defaults_log? Default is global (Y/N) 

 Set non-default value for defaults_mode? Default is http (Y/N) 

 Set non-default value for defaults_option_string? Default is option dontlognull
    option redispatch (Y/N) 

 Set non-default value for defaults_retries? Default is 3 (Y/N) 

 Set non-default value for defaults_timeout_connect? Default is 5000 (Y/N) 

 Set non-default value for defaults_timeout_client? Default is 10000 (Y/N) 

 Set non-default value for defaults_timeout_server? Default is 10000 (Y/N) 

 Set non-default value for listen_appname? Default is appname (Y/N) 

 Set non-default value for listen_ip_port? Default is 0.0.0.0:80 (Y/N) 

 Set non-default value for listen_mode? Default is http (Y/N) 

 Set non-default value for listen_balance? Default is roundrobin (Y/N) 

 Set non-default value for listen_option_string? Default is option httpclose
    option forwardfor (Y/N) 

 Set non-default value for listen_server_string? Default is  (Y/N) 

 ... All done!
 *******************************
 Thanks for installing , visit www.pharaohtools.com for more
 ******************************


 Single App Installer:
 --------------------------------------------
 HA Proxy Server: Success
 ------------------------------
 Installer Finished
 ******************************



Options
-----------                               


.. cssclass:: table-bordered

 +--------------------------+--------------------------------------+----------------+----------------------------------------------+
 | Parameters		    | Alternative Parameters		   | Options	    | Comments					   |
 +==========================+======================================+================+==============================================+
 |cleopatra HAProxy  	    | HAProxy , ha-proxy, haproxy	   | Y		    | System starts installation process	   |
 |Install		    |					   |		    |						   |
 +--------------------------+--------------------------------------+----------------+----------------------------------------------+
 |cleopatra  HAProxy 	    | HAProxy , ha-proxy, haproxy	   | N		    | System stops installation process		   |
 |Install|		    |					   |		    |						   |
 +--------------------------+--------------------------------------+----------------+----------------------------------------------+


Configuration
--------------------

This command helps in configuring the load balancing with HAproxy server. Once the below given command is executed the system provides you with the default value for each section, if there are any changes to be done, the user can provide the data. 

.. code-block:: bash

                cleopatra HAproxy configure


Benefits
--------------

* All applications access the cluster via one single IP. The topology of the database cluster masked behind HAProxy.
* It is possible to add or remove database nodes without any changes to the applications.
* Once the max number of database connections (in MySQL) reached, HAProxy queues additional new connections. This is a neat way of throttling 
  database connection requests and achieves overload protection.
