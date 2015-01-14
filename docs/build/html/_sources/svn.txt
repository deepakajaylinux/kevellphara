=======
SVN
=======

Synopsis
------------

This module assists the users to install the latest version of SVN in Ubuntu. Apache Subversion (often abbreviated SVN, after the command name svn) is a software versioning and revision control system distributed as free software under the Apache License.[1] Developers use Subversion to maintain current and historical versions of files such as source code, web pages, and documentation. Its goal is to be a mostly compatible successor to the widely used Concurrent Versions System (CVS). Let us see how this module facilitates in installing, uninstalling, ensuring the subversion in ubuntu.

Help Command
---------------------

The help command guides the users regarding the purpose and as well as about the options that are included in the SVN. It lists out the alternative parameters of SVN. It also describes the syntax for install, uninstall, ensuring the SVN. The help command for SVN module is shown as below.

.. code-block:: bash
	
		cleopatra svn help

The syntax for declaring the help command is not case sensitive which is an added advantage. The following screenshot visualize you about the help command under SVN.

Installation
---------------

The command used for installing the SVN to the ubuntu is shown below.

.. code-block:: bash
		
		cleopatra svn install

After inputting the command above, the following operations occurs as shown in tabular format.

.. cssclass:: table-bordered

 +-----------------------------+----------------------------------+----------------+---------------------------------------------+
 |	Parameters  	       | Alternative Parameter            |	Option	   | 		Comments		         |
 +=============================+==================================+================+=============================================+
 |Install SVN? (Y/N)	       |Instead of SVN, we can use svn    |Y(Yes)	   |If the user wish to proceed the installation |
 |		 	       |also		                  |		   |process they can input as Y.		 |
 +-----------------------------+----------------------------------+----------------+---------------------------------------------+
 |Install SVN? (Y/N)	       |Instead of SVN, we can use svn    |N(No)	   |If the user wish to quit the installation	 |
 |		 	       |also		                  |		   |process they can input as N.|		 |
 +-----------------------------+----------------------------------+----------------+---------------------------------------------+


If the user proceeds the installation process, during execution of installation the following process occurs:

* Reads package lists.
* builds dependency tree.
* reads state information.
* lists out extra packages installed.
* lists out new packages installed.
* number of files upgraded, newly installed, removed, not upgraded.
* Finally, the installation of SVN gets completed. The following screenshot depicts you about the process of installing SVN in ubuntu.

Un install
-------------

The command used for un installing the SVN to the ubuntu is shown below.

.. code-block:: bash

		cleopatra svn uninstall

After inputting the command above, the following operations occurs as shown in the tabular format.


.. cssclass:: table-bordered

 +-----------------------------+----------------------------------+----------------+------------------------------------------------+
 |	Parameters  	       | Alternative Parameter            |	Option	   | 		Comments		            |
 +=============================+==================================+================+================================================+
 |Uninstall SVN? (Y/N)	       |Instead of SVN, we can use svn    |Y(Yes)	   |If the user wish to proceed the un-installation |
 |		 	       |also		                  |		   |process they can input as Y.	  	    |
 +-----------------------------+----------------------------------+----------------+------------------------------------------------+
 |Uninstall SVN? (Y/N)	       |Instead of SVN, we can use svn    |N(No)	   |If the user wish to quit the un-installation    |
 |		 	       |also		                  |		   |process they can input as N.|		    |
 +-----------------------------+----------------------------------+----------------+------------------------------------------------+
 




If the user proceeds the un installation process, during execution of un installation the following process occurs:

* Reads package lists.
* builds dependency tree.
* reads state information.
* lists out packages that are automatically installed.
* lists out packages that are removed.
* number of files upgraded, newly installed, removed, not upgraded.

Finally, the un installation of SVN gets completed. The following screenshot depicts you about the process of un installing SVN in ubuntu.

Ensure
---------

The command used for ensuring SVN is shown below.

.. code-block:: bash

		cleopatra svn ensure

The ensure process performs the following functions:

* It will ensure whether the module is installed or not, and does not checks the version.
* If the module is already installed it will report as it is already existed.
* If the module is not available in the user machine, then it will proceed installation.

The following screenshots depicts the process of ensuring.

Benefits
-----------

* The parameters used in declaring the help and installations, uninstall, ensure are not case sensitive, which is added advantage while compared to others.
* The user can ensure about the availability before proceeding the installation.
* It will not overwrite the packages, hence it is less time-consuming.
