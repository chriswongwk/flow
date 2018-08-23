.. title:: Nutanix Flow

.. toctree::
  :maxdepth: 2
  :caption: Labs
  :name: _labs
  :hidden:

  enable_flow/enable_flow
  quarantine_vm/quarantine_vm
  isolate_environments/isolate_environments
  secure_app/secure_app

.. toctree::
  :maxdepth: 2
  :caption: Optional Labs
  :name: _optional_labs
  :hidden:

  flow_visualization/flow_viz

.. toctree::
  :maxdepth: 2
  :caption: Appendix
  :name: _appendix
  :hidden:

  appendix/glossary
  appendix/otherstuff

.. _getting_started:

---------------
Getting Started
---------------

Welcome to Partner SE community of Hong Kong 

**Just One Thing. The HOL is simple and short. Read carefully, do not skip.** 

What's New
++++++++++

- Workshop updated for the following software versions:
  - AOS 5.6
  - Prism Central 5.6

Access Instructions
+++++++++++++++++++

The Nutanix Hosted POC environment can be accessed a number of different ways:

Citrix XenDesktop
.................

https://citrixready.nutanix.com - *Accessible via the Citrix Receiver client or HTML5*

Or, 

VMware Horizon View
...................

https://hostedpoc.nutanix.com  - *Accessible via the View client or HTML5*


**Nutanix Employees** - Use your NUTANIXDC credentials

**Non-Employees** - **Username:** POCxxx-User01 (up to POCxxx-User20), **Password:** partnerSE/4u

We have 4 cluster today, each cluster will be shared with 10 participants. You will be informed your cluster number and user number before you start your HOL.

POC-015

POC-023

POC-044

POC-050

If your VDI is slow try to use this VPN.

Non-Employee Pulse Secure VPN
https://lab-vpn.nutanix.com - Username: POCxxx-User01 (up to POCxxx-User20), Password: partnerSE/4u

Under Client Application Sessions, click Start to the right of Pulse Secure to download the client.

Install and open Pulse Secure.

Add a connection:

Type - Policy Secure (UAC) or Connection Server
Name - HPOC VPN
Server URL - lab-vpn.nutanix.com
