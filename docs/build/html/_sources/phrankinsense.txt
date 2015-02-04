=================
Phrankinsense
=================

Synopsis
------------------

This tool helps the user to install and update phrankinsense under Cleopatra in pharaoh tools. Automation of the build should include automating the integration, which often includes deployment into a production-like environment. In many cases, the build script not only compiles binaries, but also generates documentation, website pages, statistics and distribution media such as Red Hat. It comforts with Ubuntu and Cent OS.

Help command
-----------------------

The help command leads the users regarding the purpose and as well as about the options that are included in the Phrankinsense modules. The help command lists out the alternative parameters of Phrankinsense under Cleopatra module. It also describes the syntax for installing the user’s updation. The help command for Phrankinsense is shown below.

.. code-block:: bash

 		cleopatra Phrankinsense help

The following screen shot shows the full effort of Phrankinsense.

.. code-block:: bash

 kevells@corp:/# cleopatra Phrankinsense help

 ******************************


  This command allows you to install or update Phrankinsense.

  Phrankinsense, phrankinsense

        - install
        Installs the latest version of phrankinsense
        example: cleopatra phrankinsense install

        - ensure
        Ensures phrankinsense is installed
        example: cleopatra phrankinsense ensure

        - uninstall
        Uninstalls the latest version of phrankinsense
        example: cleopatra phrankinsense uninstall
 ------------------------------
 End Help
 ******************************


Installation
--------------------

This is a tool that sits under cleopatra  and pulls down clean copies of the user codebase and does full builds, from scratch, all the time. This command is used to  install latest version of Phrankinsense. The command used for installation is as follows.

.. code-block:: bash

	cleopatra Phrankinsense install


After inputs the command the system can ask

install Phrankinsense?(Y/N)

If the user gives Y then Phrankinsense will be installed. The following Screen shot demonstrate it .


.. code-block:: bash


.. cssclass:: table-bordered


 +-----------------------------+----------------------+-----------------------------------+-------------------------------------+
 | Parameters		       | Directory(default)   | Options				  | Comments			        |
 +=============================+======================+===================================+=====================================+
 |Data directory (Default)     | Yes                  | “/opt/Phrankinsense”		  | It will install Phrankinsense       |
 |			       |		      |					  | under Cleopatra		        |
 +-----------------------------+----------------------+-----------------------------------+-------------------------------------+
 |Data directory	       | No		      | End slash			  | The user has to a specify the path  |
 +-----------------------------+----------------------+-----------------------------------+-------------------------------------+
 |Executor directory(Default)  | Yes		      | “/usr/bin”			  | It will  install executor directory |
 +-----------------------------+----------------------+-----------------------------------+-------------------------------------+
 |Executor directory	       | No		      | No trailing slash 		  | The user gives input as directory   |
 |			       |		      |					  | name.|			        |
 +-----------------------------+----------------------+-----------------------------------+-------------------------------------+


Uninstall
--------------

This command is used to Uninstall the latest version of Phrankinsense. The command used for Uninstallation is as follows.

.. code-block:: bash

		cleopatra Phrankinsense Uninstall

After inputs the command the system can ask

Uninstall Phrankinsense?(Y/N)

If the user gives Y then Phrankinsense will be Uninstalled. The following Screen shot demonstrate it .

.. code-block:: bash

.. cssclass:: table-bordered

 +-----------------------------+----------------------+-----------------------------------+-------------------------------------+
 | Parameters                  | Directory(default)   | Options                           | Comments                            |
 +=============================+======================+===================================+=====================================+
 |Data directory (Default)     | Yes                  | “/opt/Phrankinsense”              | It will uninstall Phrankinsense     |
 |                             |                      |                                   | under Cleopatra                     |
 +-----------------------------+----------------------+-----------------------------------+-------------------------------------+
 |Data directory               | No                   | End slash                         | The user has to a specify the path  |
 +-----------------------------+----------------------+-----------------------------------+-------------------------------------+
 |Executor directory(Default)  | Yes                  | “/usr/bin”                        | It will uninstall executor directory|
 +-----------------------------+----------------------+-----------------------------------+-------------------------------------+
 |Executor directory           | No                   | No trailing slash                 | The user gives input as directory   |
 |                             |                      |                                   | name.|                              |
 +-----------------------------+----------------------+-----------------------------------+-------------------------------------+




Ensure
----------

Ensure process used to check the  Phrankinsense  installed in the user  system or not. The following command helps the user to ensure.

.. code-block:: bash

		cleopatra Phrankinsense ensure

The following screen shot shows its functions.



Benefits
----------------

* Used to Install Phrankinsenses possible.
* Suitable to work with Ubuntu and centos.
* Non case sensitivity.
* Automation in updated version.
* Reliability, Availability, serviceability with other connections.

