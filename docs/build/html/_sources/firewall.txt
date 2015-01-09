===========
Firewall
===========

Synopsis
---------

A firewall is a network security system that controls the incoming and outgoing network traffic based on an applied rule set. Firewalls exist both as a software solution and as a hardware appliance. 

Help command
-------------

This help command assist the user about Cleopatra. It guides the user permission.
The user can do the modification as per wish. Help image will guide the user. Let’s visualize it.

.. code-block:: bash

  cleopatra Firewall help

Options
---------

Firewalls rules can be customized as per your needs, requirements & security threat levels. The user can create or disable firewall rules based on such conditions as:


parameter
functions
Comments
IP address
Blocking off a certain IP address or a range of IP addresses, which you think are predatory

Enable
Enable system firewall
Cleopatra firewall enable
Disable
Disable system firewall
Cleopatra firewall disable
Allow
Allow firewall rule
Cleopatra firewall allow –firewall-rule=”ssh/tcp”
Deny
Allow connection attempt to be ignored and time out
Cleopatra firewall deny –firewall-rule=”ssh/tcp”
Reject
Terminate connection attempts with an error to the connector
Cleopatra firewall reject –firewall-rule=”ssh/tcp”
Limit
Ufw will deny connections if an IP address has initiate 6  or attempted to more connection in the last 30 seconds.
Cleopatra firewall limit –firewall-rule=”ssh/tcp”
Delete
Delete a firewall rule
Cleopatra firewall delete –firewall-rule=”ssh/tcp”
Insert
Insert a  firewall rule
Cleopatra firewall insert –firewall-rule=”ssh/tcp”
Reset
Reset a firewall rule
Cleopatra firewall reset –firewall-rule=”ssh/tcp”
default
Default policy, should be allow, deny or reject.
Cleopatra firewall default – policy=”deny”




Benefits
The firewall prevents unwanted access to the system over a network connection by identifying and preventing communication over risky ports.

System communicate over many different recognized ports, and the firewall will tend to permit these without prompting or alerting the user.

Firewalls can also detect "suspicious" activity from the outside.

The user can set their rule according to their wish.


