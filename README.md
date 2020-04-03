XenVusb - The Xen Paravitual VUSB Class Driver for Windows
============================================================

The XenVusb package consists of a single device driver:

*    xenvusb.sys is a bus driver which attaches to a virtual device created
     by XenBus and creates a child device for each VUSB device for XENUSBDEVICE
     to attach to.

Quick Start Guide
=================

Building the driver
-------------------

See BUILD.md

Installing the driver
---------------------

See INSTALL.md

Driver Interfaces
=================

See INTERFACES.md
