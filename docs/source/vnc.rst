===========
VNC
===========

Synopsis
-------------

This module provides assistance for installing VNC4server via apt get. It enables connectivity for virtual machine. It facilitates ensuring before installation.

Help Command
--------------

The help command provides an awareness regarding the VNC module. It also describes about the options that can be performed under this VNC module.
The help command for this VNC module is given below,

.. code-block:: bash

	Cleopatra vnc help

The screen shot given below shows you an pictorial representation regarding the usage of help command under VNC module.

.. code-block:: bash

	Kevells@corp:/# cleopatra vnc help
	******************************


        This command allows you to install VNC, the popular Virtual Machine Solution.

	 VNC, vnc

        - install
        Installs VNC through apt-get
        example: cleopatra vnc install

	------------------------------
	End Help
	******************************


Installation
------------------
.. code-block:: bash
	
	Cleopatra vnc install

After inputting the command as given above, the following operations takes places.

.. cssclass:: table-bordered

+------------------------------------------------+-------------+-------------------------------+
|  Parameters                                    |  Required   |  Comment                      |
+================================================+=============+===============================+
|  Install VNC? (Y/N)                            |  Y(YES)     |  If the user wish to proceed  |
|                                                |             |  with installation process,   | 
|                                                |             |  they can input as Y.         |
+------------------------------------------------+-------------+-------------------------------+ 
|  Install VNC? (Y/N)                            |  N(NO)      |  If the user wish to quit the |
|                                                |             |  installation process, they   | 
|                                                |             |  can quit simply by using N.  |
+------------------------------------------------+-------------+-------------------------------+
|  Install ApacheReverseProxyModules (Y/N)       |  N(NO)      |  If the user inputs as N,the  |
|                                                |             |  process will gets quit from  |
|                                                |             |  installation                 |
+------------------------------------------------+-------------+-------------------------------+

 .. rubric:: While installing the VNC server it performs the following operations as given below:

* Reads the package lists, state information,
* Builds the dependency tree.
* Installs the xbase-clients as extra packages, vnc-java as suggested packages.
* Installs vnc4server xbase-clients as new packages.
* It also displays the number of files upgraded, newly installed, removed, not upgraded.

The screen shot as given below, explains the users graphically regarding the process of installation.

If the vnc server already exists in the users machine, it will throws an exception message as the vnc server is already installed. The following screenshot gives an pictorial representation regarding the exception message.

Benefits
---------------

* It allows the process of ensuring before installation.
* It facilitates installation via apt get.
* It enables the virtual machine connectivity.
* In case of VNC server is already exist, it throws exceptional message during the process of ensuring.
