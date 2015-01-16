================
JenkinsPlugins
================

Synopsis
-------------

Jenkins is popular to build server. Jenkins is an open source continuous integration tool written in Java. Jenkins provides continuous integration services for software development. 

Plugins have been released for Jenkins that extend its use to projects written in languages other than Java. Plugins are available for integrating Jenkins with most version control systems and big databases. Many build tools are supported via their respective plugins. Plugins can also change the way Jenkins looks or add new functionality. Builds can generate test reports in various formats supported by plugins (JUnit support is currently bundled) and Jenkins can display the reports and generate trends and render them in the GUI.

Help Command
-----------------

This command helps to determine the usage of JenkinsPlugins module. The user will come to know about the different ways/format to execute this module. This command guides the end user to know the purpose of this command. Below given are the command and the screenshot of the same. 

.. code-block:: bash
             
   		Cleopatra JenkinsPlugins help





Installation
----------------
 This command allows you to install a bunch of plugins that we recommend for
 PHP builds in Jenkins. If the user needs to install Jenkins module in machine, the below given command will execute the process of installation. 

.. code-block:: bash
        
		Cleopatra JenkinsPlugins install













Options
-----------     

.. cssclass:: table-bordered

 +-----------------------------+----------------------------------+----------------+------------------------------------------------+
 |	Parameters  	       | Alternative Parameter            |	Option	   | 		Comments		            |
 +=============================+==================================+================+================================================+
 |Cleopatra  JenkinsPlugins    |Either of the four alternative 	  |Y		   |Once the user provides the option, System starts|	
 |Install		       |parameter can be used in command- |		   |installation process			    |
 |			       |JenkinsPlugins,  		  |		   |						    |	
 |			       |jenkinsplugins,			  |		   |						    |
 |			       |jenkins-plugins, 		  |                |						    |
 |			       |jenkins-plugs			  |		   |						    |
 |			       |eg: Cleopatra jenkins-plugins	  |		   |						    |
 |			       |Install				  |		   |						    |
 +-----------------------------+----------------------------------+----------------+------------------------------------------------+
 |Cleopatra  JenkinsPlugins    |Either of the four alternative 	  |N		   |Once the user provides the option, System Stops |	
 |Install		       |parameter can be used in command- |		   |installation process			    |
 |			       |JenkinsPlugins,  		  |		   |						    |	
 |			       |jenkinsplugins,			  |		   |						    |
 |			       |jenkins-plugins, 		  |                |						    |
 |			       |jenkins-plugs			  |		   |						    |
 |			       |eg: Cleopatra jenkins-plugins	  |		   |						    |
 |			       |Install|			  |		   |						    |
 +-----------------------------+----------------------------------+----------------+------------------------------------------------+
                          

Benefits
--------------

* The plugin will give you a report on how much every plugin will be used in all of your jobs . Therefore it will analyze the used extension points of each job.
* This plugin gives you the possibility to analyze the usage of your installed plugins.
