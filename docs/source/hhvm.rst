======
HHVM
======

Synopsis
------------

This module facilitates installing and un installing the HHVM which is a popular build server to your machine. HipHop Virtual Machine (HHVM) is a process virtual machine based on just-in-time (JIT) compilation, serving as an execution engine for PHP and Hack programming languages. By using the principle of JIT compilation, executed PHP or Hack code is first transformed into intermediate HipHop byte code (HHBC), which is then dynamically translated into the x86-64 machine code, optimized and natively executed. Let us see about the HHVM module in upcoming topics.

Help Command
------------------

The help command guides the users regarding the purpose and as well as about the options that are included in the HHVM module. It lists out the alternative parameters of HHVM module. It also describes the syntax for installing the HHVM module. The help command for HHVM module is shown as below.

.. code-block:: bash

		cleopatra HHVM help

The syntax for declaring the help command is not case sensitive which is an added advantage. The following screenshot visualize you about the help command under HHVM.

Installation
----------------

The command used for installing the HHVM to the users machine is shown below.

.. code-block:: bash

		cleopatra HHVM install

After inputting the command above, the following process occurs as shown in the tabular format.

.. cssclass:: table-bordered

 +-----------------------------+----------------------------------+----------------+---------------------------------------------+
 |	Parameters  	       | Alternative Parameter            |	Options	   | 		Comments		         |
 +=============================+==================================+================+=============================================+
 |Install The Oracle Java      |Inspite of HHVM we can use hhvm	  |Y(Yes)	   |If the user wish to proceed the installation |
 |JDK 1.7? (Y/N)               |also.			          |		   |process they can input as Y.		 |
 +-----------------------------+----------------------------------+----------------+---------------------------------------------+
 |Install The Oracle Java      |Inspite of HHVM we can use hhvm   |N(No)	   |If the user wish to quit the installation    |
 |JDK 1.7? (Y/N) 	       |also.		       		  |	    	   |process they can input as N.|		 |
 +-----------------------------+----------------------------------+----------------+---------------------------------------------+



Finally, installation process gets completed. The following screenshot pictorially represents the process of installing HHVM.

Un installation
--------------------

The command used for un installing the hhvm is shown below.

.. code-block:: bash

		cleopatra HHVM uninstall

Benefits
------------

* The parameters used in help and installation and un installation operations are not case sensitive which is an added advantage while compared to others.
* It is well-to-do in both Ubuntu and as well as Cent OS.
* HHVM has the ability to use live type information to produce more efficient native code, leading to higher web server throughput and lower latency.
