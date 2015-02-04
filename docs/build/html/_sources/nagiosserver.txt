==============
NagiosServer
==============

Synopsis
-------------

Nagios is an open source computer system monitoring, network monitoring and infrastructure monitoring software application. Nagios offers monitoring and alerting services for servers, switches, applications, and services. It alerts the users when things go wrong and alerts them a second time when the problem has been resolved.

Nagios, originally created under the name NetSaint, was written and is currently maintained by Ethan Galstad along with a group of developers who are actively maintaining both the official and unofficial plugins. Nagios was originally designed to run under Linux but also runs well on other Unix variants. It is free software licensed under the terms of the GNU General Public License version 2 as published by the Free Software Foundation.

Help Command
----------------------

This command helps to determine the usage of Nagios module. The user will come to know about the different way/format to execute this module. This command guides the end user to know the purpose of this command. Below given are the command and the screenshot of the same. 

.. code-block:: bash
        
	        cleopatra nagios help


The pictorial screenshot of the above command is listed below,

.. code-block:: bash

 kevell@corp:/# cleopatra nagios help
 ******************************


  This command is part of Core and provides you with a method by which you can install Nagios.

  NagiosServer, nagios-server, nagiosserver, nagios

        - install
        Installs Nagios Network Monitoring Server
        example: cleopatra nagios-server install

 ------------------------------
 End Help
 ******************************


Installation
----------------

This command helps in installing the Nagios in system. The below given command will execute the process of installation.

.. code-block:: bash
        
	        cleopatra nagios install

The pictorial representation of the above command is listed below,

.. code-block:: bash



Options
-----------                               

.. cssclass:: table-bordered

 +------------------------+----------------------------------------------------+---------------+-----------------------------------+
 | Parameters		  | Alternative Parameters			       | Options       | Comments			   |
 +========================+====================================================+===============+===================================+
 |cleopatra nagiosserver  | There are four alternative parameters which can be | Y	       | System starts installation process|
 |Install		  | used in command line. 			       | 	       |			           |
 | 			  | NagiosServer, nagios-server, nagiosserver, nagios  |               |				   |
 |			  | Eg: cleopatra nagios install/ 		       |               |				   |
 |			  | 	cleopatra nagiosserver install		       |               |				   |
 +------------------------+----------------------------------------------------+---------------+-----------------------------------+
 |cleopatra nagiosserver  | There are four alternative parameters which can be | N             | System stops installation process |
 |Install                 | used in command line.                              |               |                                   |
 |                        | NagiosServer, nagios-server, nagiosserver, nagios  |               |                                   |
 |                        | Eg: cleopatra nagios install/                      |               |                                   |
 |                        |     cleopatra nagiosserver install|                |               |                                   |
 +------------------------+----------------------------------------------------+---------------+-----------------------------------+



Benefits
--------------

* Monitoring of network services (SMTP, POP3, HTTP, NNTP, ICMP, SNMP, FTP, SSH)
* Monitoring of host resources (processor load, disk usage, system logs) on a majority of network operating systems, including Microsoft 
  Windows with the NSClient++ plugin or Check MK.
* Monitoring of anything else like probes (temperature, alarms,etc.) which have the ability to send collected data via a network to 
  specifically written plugins
* Monitoring via remotely run scripts via Nagios Remote Plugin Executor
* Remote monitoring supported through SSH or SSL encrypted tunnels.
* A simple plugin design that allows users to easily develop their own service checks depending on needs, by using their tools of choice (shell  scripts, C++, Perl, Ruby, Python, PHP, C#, etc.)
* Available data graphing plugins
* Parallelized service checks
* The ability to define network host hierarchies using 'parent' hosts, allowing the detection of and distinction between hosts that are down or  unreachable
* Contact notifications when service or host problems occur and get resolved (via e-mail, pager, SMS, or any user-defined method through plugin  system)
* The ability to define event handlers to be run during service or host events for proactive problem resolution
* Automatic log file rotation
* Support for implementing redundant monitoring hosts
* An optional web-interface for viewing current network status, notifications, problem history, log files, etc.
* Data storage via text files rather than database
