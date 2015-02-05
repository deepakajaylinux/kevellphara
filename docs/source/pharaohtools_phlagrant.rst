=============
PharaohTools
=============

Synopsis
------------

The Pharaoh tool module assists in installing Dapperstrano, Testingamen, Jrush, generating Phlagrant reports. It facilitates the users to ensure the availability before installations. Only missing modules can be installed specifically.

Help Command
---------------------

The help command guides the users about how to make use of this particular module under Phlagrant.

It also make them aware of the options that can be performed on this specific module.

It lists outs the alternative parameters along with the syntax for installing the pharaoh tools.

The command for using the help option is shown below,

.. code-block:: bash

		phlagrant pharaoh-tools help


The screen shot as shown below gives you a pictorial representation regarding the usage of help command.

.. code-block:: bash


Installation
--------------

The pharaoh tool module acts as a shorter route that envelops installation of Dapperstrano, Testingamen, Jrush. If any one particular module is missing among the three, the specific module alone will be installed which is an added advantage. The ensure process plays an important role in grabbing data's regarding the availability of modules.

The command used for installation process under Pharaoh tool is given below,

.. code-block:: bash

	Phlagrant pharaoh-tools install

After entering the command above, the installation process starts executing and proceeds in the following ways as depicted from in the table,


.. cssclass:: table-bordered

 +---------------------------------+--------------------------+----------------------------------------------------+
 | Parameters			   | Available Input options  | Comment					           |
 +=================================+==========================+====================================================+
 |Install Pharaoh Tools? (Y/N)     | Y(Yes)		      | If the user wish to proceed with installation      |
 |				   | 			      | process, they can input as Y			   |
 +---------------------------------+--------------------------+----------------------------------------------------+
 |Install Pharaoh Tools? (Y/N)	   | N(No)		      | If the user wish to quit the installation process, |
 |				   |			      | they can quit simply by using N|		   |
 +---------------------------------+--------------------------+----------------------------------------------------+


While installing the Pharaoh tool the following steps takes place:

Ensure
----------

* The pharaoh tool ensures the available modules.
* While ensuring, It won't check about the versions.

Dapperstrano
------------------

* The module dapperstrano reports itself as installed, in case of existence. 
* It also checks the version for dapperstrano module.
* If the dapperstrano module is not available in the machine, then automatically dapperstrano will progress to install.

Testingamen
------------------

* After completion of installing dapperstrano, it will ensure the Testingamen module. 
* The module Testingamen reports itself as installed, in case of existence. 
* If the Testingamen module is not available in the machine, then automatically Testingamen will progress to install.

Jrush
--------

* After completion of installing Testingamen, it will ensure the Jrush module.
* The module Jrush reports itself as installed, in case of existence. 
* If the Jrush module is not available in the machine, then automatically Jrush will progress to install.
* If all the three modules are already existing, then it will show exceptional message as given in the screenshot below,


Additional Options
-------------------------

While installing Dapperstrano, Testingamen, Jrush the following options are required as input from the user. Let us see about, the additional options that can be specified by the users if they wish, is represented in a tabular format as shown below.



.. cssclass:: table-bordered

 +----------------------------+-------------------------------------------+--------------------+--------------------------------------------+
 | Parameters		      | Path					  | Option	       | Comment		  		    |
 +============================+===========================================+====================+============================================+
 |Program data directory      | "/opt/testingkamen(corresponding module)" | Yes		       | If the user to proceed installation with   |
 |(Default)		      | 					  |		       | the default program data directory they    |
 |			      |						  |		       | can input as Yes			    |
 +----------------------------+-------------------------------------------+--------------------+--------------------------------------------+
 |Program data directory      | User specific				  | No(End slash)      | If the user wish to proceed with their own |
 |			      |						  |		       | program data directory, they can input as  |
 |			      |						  |		       | N, and in hand specify they own location.  |
 +----------------------------+-------------------------------------------+--------------------+--------------------------------------------+
 |Program executor directory  | "/usr/bin"			          | Yes		       | If the user to proceed installation with   |
 |(Default)		      |						  |		       | the default program executor directory     |
 |			      | 				          |		       | they can input as Yes			    |
 +----------------------------+-------------------------------------------+--------------------+--------------------------------------------+
 |Program executor directory  | User specific				  | No(End slash)      | If the user wish to proceed with their own |
 |			      |						  |		       | program executor directory, they can       |
 |			      |						  |		       | input as N, and in hand specify they       |
 |			      |						  | 		       | own location.|				    |
 +----------------------------+-------------------------------------------+--------------------+--------------------------------------------+



While installing it will specify the location of git clone, displays the number of objects , receiving objects, resolving deltas, connectivity.

The following screen shot explains you graphically about the process involved in installation of Pharaoh tool.


.. code-block:: bash


Benefits
-----------

* It facilitates the users to ensure before installation.
* In case of any particular module is missing, the user can proceed to install that particular module alone.
* The user can specify their own path or location for program data directory and executor directory.
* If any particular module already exists in the machine, then the installation tool will throw an exception message as it is already 
  installed.
* It avoids unwanted overwriting of modules, hence it is time saving.

