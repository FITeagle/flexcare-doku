```````````````````````````````
The FUSECO Playground
```````````````````````````````

.. contents:: Table of Contents


Introduction
============

FUSECO playground offers a unique, independent and open testbed for research and prototype development in multi-access network environments (WLAN/2G/3G/4G-LTE), sensor networks, SDN/OpenFlow&NFV cloud environments. 
It has to be considered as a testbed and not a production environment, in terms of scalability. Some resources require exclusive reservation only e.g. no parallel wireless experiments. 
The FUSECO terms and conditions are available `online <http://www.fokus.fraunhofer.de/en/fokus_testbeds/fuseco_playground/_files/FUSECO_Playground_Terms_and_Conditions.pdf>`_.


Overview of Resources
=====================

The FUSECO Playground consists of the following major components:

* Virtual	Machines	running	on	OpenStack	
* WiFi	APs
* LTE	Femto	Cells
* 3G	Femto	Cells
* 2G	Femto	Cells
* Radio	Signal	Attenuation	System
* Radio	Signal	Shield	Box
* OpenIMS	Core
* OpenIMS	Clients	Linux
* OpenIMS	Clients	Android
* OpenEPC	as	a	Service
* OpenEPC	Clients	Linux
* OpenEPC	Clients	Android
* Monitoring	Systems

See :ref:`resourcedetails-label` for more details. 

Getting an Account
==================

In order to access the FUSECO Playground, a user has currently main two possibilities.

SSH Credentials
---------------

This is a manual process and a mail should be sent to `info@fuseco-playground.org <mailto:info@fuseco-playground.org>`_.

.. _sfaaccess-label:

SFA Credentials
---------------

A user needs either a X.509 certificate from a trusted federation, such as Fed4FIRE, or from the FUSECO Playground.
To get credentials from the FUSECO Playground:

#. Visit https://fuseco.fokus.fraunhofer.de/#registration
#. Fill out the form
#. Once you are signed in, click on you name in the upper right corner and choose "Download Certificate"
#. Enter a passphrase for a "New Keypair with Certificate" and click on "Generate"
#. Copy the content from the resulting text field and save it as "mycredentials.pem"
