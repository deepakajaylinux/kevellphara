=========
Version
=========

Synopsis
----------------

This module used to install updated version under dapperstrano. Version control  most commonly run as stand-alone applications, but revision control is also embedded in various types of operating system such as Ubuntu and Cent OS. Most version allow multiple developers to edit the same file at the same time. The first developer to "check in" changes to the central repository always succeeds. The system may provide facilities to merge further changes into the central repository, and preserve the changes from the first developer when other developers check in.It supports Ubuntu and CentOS.

Help command
-----------------------

The help command leads the users regarding the version of the dapperstrano. The options that are included in the version modules. The help command lists out the alternative parameters of version under dapperstrano module. It also describes the syntax for version. The help command for version is shown below.

.. code-block:: bash

		dapperstrano  version help

The following screen shot shows the full effort of dapperstrano.


.. code-block:: bash


 kevell@corp:/# dapperstrano Version help
 ******************************


  This command is part of Default Modules and handles Application Versioning, allowing for rollbacks and the like.

  Version, version, vrs

          - specific
          Will change back the *current* symlink to whichever available version you pick
          example: dapperstrano version specific --limit=4 --container=/var/www/applications/the-app --version=2

          - latest
          Will change back the *current* symlink to the latest created version
          example: dapperstrano version latest
          example: dapperstrano version latest --limit=3 --container=/var/www/applications/the-app

          - rollback
          Will change back the *current* symlink to the latest created version but one
          example: dapperstrano version rollback
          example: dapperstrano version rollback --limit=3 --container=/var/www/applications/the-app


      You can also apply a limit to the number of Versions to keep by using the --limit parameter
          example: dapperstrano version latest --limit=3

 ------------------------------
 End Help
 ******************************


Alternative parameter
--------------------------------

There are two alternatives available in version. They are

Version, version, VERSION

Installation
----------------

Installation includes installation of version required to make the installation in an updated version. It is a manifest process to install version module under dapperstrano. version by just using the command given below,

.. code-block:: bash

		dapperstrano version Install

After vitalize the command it will catechize input.

When the user input as yes automatically it will install version with checking from the system. If not exit the installation. The following screen shot demonstrate version and its functions.

Option
------------

.. cssclass:: table-bordered

 +--------------------------+-----------------+---------------------------------------+--------------------------------------+
 | Parameters		    | Syntax 	      | Option				      | Comments			     |
 +==========================+=================+=======================================+======================================+
 |Install version?(Y/N)	    | Yes	      | Instead of using version the user     | Installed successfully		     |
 |			    |		      | can use Version,VERSION		      | under dapperstrano module     	     |
 +--------------------------+-----------------+---------------------------------------+--------------------------------------+
 |Install version?(Y/N)	    | No	      | Instead of using version the user     | Exit the screen			     |
 |			    |		      |	can use Version,VERSION.|	      | 				     |
 +--------------------------+-----------------+---------------------------------------+--------------------------------------+


Benefits
---------------

* New version can be updated.
* It is suitable with Ubuntu and CentOS.
* Non case sensitivity
* Automation is possible
* Simple to type the commands

