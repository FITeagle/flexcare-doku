.. _resourcedetails-label:

```````````````````````````````
FUSECO Playground Resource Description
```````````````````````````````

.. contents:: Table of Contents

Femto Cells
===========
	
The Base Stations we use are commercial off-the-shelf elements. Usually they support basic functionality.

Ip.access LTE 245 F femtocells
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: _static/lte245-access-point.png
Figure: LTE245 Access Point

It is dual band capable and is available in 3GPP Bands 1/13, 4/13, 2/5 or 7/13. Supporting 2x2 MIMO with an output power of +10dBm per port, the 245 provides comprehensive LTE operation in a compact form factor.

Table: LTE 245F Key Features:
=========================== ==================================
Features                    Details
=========================== ==================================
3GPP Compliance             Compliant to 3GPP Rel 8.9.0
Number of RF Carriers       Single Carrier
3GPP Band Support           3GPP Band Support Dual Band 1/13, 4/13, 2/5 or 7/13.
Bandwidth                   10MHz
MIMO                        2x2 MIMO-Single User Downlink only
RF Average Output Power     2 x 10dBm
Modulation/Coding           16QAM U/L and D/L
Max Data Rate Throughput    13Mbps	Max Data Rate Throughput 13Mbps
Simultaneous # Active Users 4
Simultaneous # Idle Users   64
Network Interfaces          S1 over IP
Electrical Supply           12V @ 5.5A from external power brick
=========================== ==================================

**RF Capabilities**

The 245 offers dual band LTE capability within a single hardware SKU. Operation is on one band at a time (i.e. not simultaneous dual band operation) as configured by via the OAM interface. A reboot is currently required when changing the OAM configuration.
The RF subassembly used in the 245 has a maximum rating of 2 x 13dBm. However, for normal and continuous operation, the 245 should be configured such that RF output power does not exceed 2 x 10dBm unless additional heat-sinking measures have been applied.

**Throughput Performance**

The 245 platform is capable of high speed data transfer to LTE capable devices. Currently specified performance of Air Interface data rate is 13Mbps, which can be achieved for a single active user with a small rate reduction when 2 users are active. Further rate reduction is to be expected when the cell is loaded with additional users. The platform is software upgradeable to support operation up to 100Mbps downlink aggregate throughput, using 64 QAM.

**Mobility**

Idle mode mobility between the 245 and surrounding LTE or UMTS 3G cells is supported. The platform is software upgradable to support Active Mode handover.

**Operational Range**

Useful cell radius is a function of many variables including antenna types, number of users, throughputs and so on. The 245 is specified to support 900m range in terms of its baseband capability.

**GPS**
The 245 is supplied with integrated GPS hardware. In principle this could be used for various functions such as location and synchronisation subject to appropriate software support (not currently supplied).

**Network Interfaces**
The ‘S1’ network interface is presented via two 1Gbps Ethernet ports.

Physical Interfaces
 
.. figure:: _static/lte245-lte-femto-cell.png
Figure 8: LTE245 LTE femto cell

The following physical interfaces are presented on the enclosure panel:

* DC power jack
* 2 off RJ45 Ethernet
* Micro USB
* 2 off SMA female RF
* 9-way RS-232 serial Console port
* GPS receptacle (not used)
* Telephony/modem port (not used)

ip.access Nano3G E16 (model 239A) UMTS IMT 2100
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The full +24 dBm (250mW) output power gives the E-class picocells the range to cover medium and large office buildings, and for the largest deployments the E-class can connect directly into an active DAS system. The flexibility is further enhanced by the high precision oscillator, giving fast start up in areas where no macro network can penetrate.

Features:

* Up to 16 simultaneous active users - (each with concurrent voice and high-speed data sessions)
* +24 dBm (250mW) output power
* Available for Bands 1, 2/5 and 4

ip.access nanoBTS (DCS 1800)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Each nanoBTS is a single TRX which can support up to 14 simultaneous voice calls using dynamic AMR with half-rate. For high traffic locations, where even greater capacity is needed, up to 4 nanoBTS can used to create a 2, 3 or 4 TRX cell. The nanoBTS picocell offers:

* Controllable output power up to 23dBm giving an indoor range up to 200m
* Simple deployment with a single Ethernet connection for power, traffic and signalling
* GPRS and EDGE data essential Blackberry® and enterprise applications
* Models for the 850, 900, 1800 and 1900MHz bands
* Network Listen™ to optimize handover configuration
