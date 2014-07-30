.. _overview:

Product Overview
================

The VIA EPIA-P910 Pico-ITX mainboard is a compact native x86 mainboard
optimized for systems in embedded and multimedia applications. It can also
be used for various domain applications such as medical PC, industrial PC, and
etc. The mainboard is based on the VIA VX11H Media System Processor that
features the VIA Chrome TM 645/640 DX11 with 2D/3D graphics and video
accelerators for rich digital media performance.

The VIA EPIA-P910 mainboard has integrated HDMI® port, RJ-45, Dual USB 3.0
stack and typical VGA port. The I/O companion card P910-A is the optional
expansion connector provided by EPIA-P910. The P910-A I/O companion card
is connected through onboard pin headers carrying the front panel I/O such as
audio Jack, 2 USB 2.0 Ports, LED indicator and power button.

The VIA EPIA-P910 has a powerful, secure, and efficient VIA QuadCore
processor. The VIA QuadCore processor includes the VIA AES Security Engine,
VIA CoolStream TM Architecture and VIA PowerSaver TM Technology.

The VIA EPIA-P910 includes one 1333 MHz DDR3 SODIMM slot that support
up to 8 GB memory size. The VIA EPIA-P910 provides support for high fidelity
audio with its included VIA VT2021 High Definition Audio codec. In addition it
supports two SATA 3.0 Gb/s storage devices and fully compatible with
Microsoft® and Linux operating systems.

Key Features and Benefits
-------------------------

VIA QuadCore Processor
^^^^^^^^^^^^^^^^^^^^^^

The VIA QuadCore is a 64-bit superscalar x86 quad core (Isaiah) processor
combine on two dies. It is based on advanced 40 nanometer process
technology packed into an ultra compact NanoBGA2 package measuring
21mm x 21mm. The VIA QuadCore processor delivers a superb performance
on multi-tasking, multimedia playback, productivity and internet browsing in a
low power budget. In addition, it is ideal for most of multi-display
environment, and embedded system applications such as industrial PCs, test
machines, measuring equipment, digital signage, medical PCs, monitoring
systems, gaming machines, in-vehicle entertainment, etc.

VIA VX11H MSP Chipset
^^^^^^^^^^^^^^^^^^^^^

The VIA VX11H is the fourth generation, highly integrated Media System
Processor which provides high quality digital video streaming and high
definition video playback. It features the VIA Chrome™ 645/640 DX11 2D/3D
graphics and video processor, High Definition video decoder supports DDR3
1333 controller and USB 3.0 interface.

The VIA VX11H offers superb-graphics performance, immersive visual
experience, and supports DirectX 11.0 that allows realistic 3D rendering and
increased visual acuity. The VIA VX11H is based on a highly sophisticated
power efficient architecture that enables such rich integration into a compact
package.

Expansion Option
^^^^^^^^^^^^^^^^

The EPIA-P910 further proves its versatility by providing an optional expansion
connector.

The P910-A I/O companion card is connected through onboard pin headers
carrying the front panel I/O such as audio Jack, 2 USB 2.0 Ports, LED indicator
and power button.

The companies using the EPIA-P910 with P910-A I/O companion card obtain
the maximum benefits and enable to slowly roll out upgrades as necessary
instead of having to replace everything all at once.

Product Specifications
----------------------

* **Processor**

  * VIA QuadCore 1.0+ GHz NanoBGA2

    * Supports 800MHz Front Side Bus

  * x86 and x64 compatible
  * 21 mm x 21 mm FCBGA

* **Chipset**

  * VIA VX11H MSP chipset
  * 33 mm x 33 mm FCBGA

* **Graphics**

  * Integrated VIA Chrome 645/640 DX11 2D/3D graphics and video processor
  * MPEG2, WMV9/VC1, H.264 Full HD video decoder
  * UMA supporting CRT/HDMI/LVDS
  * Optimized Unified Memory Architecture (UMA)
  * Support frame buffer size from 256MB to 512MB

* **System Memory**

  * 1 x SODIMM socket supporting DDR3 1333/1066 MHz
  * Supports up to 8 GB memory size

* **Onboard Peripherals**

  * Serial ATA

    * Supports up to two SATA 3.0 Gb/s

  * Onboard LAN

    * VIA VT6130 PCIe Gigabit Ethernet controller

  * Onboard Audio

    * VIA VT2021 High Definition Audio Codec

  * Onboard Super I/0

    * Fintek F81801U-I Super I/O controller

* **Onboard I/O Connectors**

  * 1 x KB/MS, LPC, SMBus and GPIO combination pin header connector
  * 1 x Front panel, Audio (Line-in/Line-out/Mic-in/SPDIF-out), USB 2.0 combination pin header connector
  * 3 x PCIe, 3 x USB 2.0, DVP and SDIO combination board-to-board connector for expansion card
  * 1 x Single-channel 18/24-bit LVDS panel connector
  * 1 x SATA power connector (with Y-cable for 2)
  * 1 x System/CPU fan connector
  * 1 x LVDS panel power selector jumper (5V/3.3V)
  * 1 x LVDS backlight voltage selector jumper (5V/12V)
  * 1 x SPI flash connector
  * 1 x CMOS external battery connector
  * 1 x DC-In power connector (+12V±5%)

* **Back Panel I/O**

  * 1 x Mini HDMI port (Type C)
  * 1 x VGA port
  * 1 x GigaLAN port
  * 2 x USB 3.0 ports

* **BIOS**

  * AMI APTIO UEFI BIOS
  *  32 Mbits SPI flash memory

* **Supported Operating System**

  * Microsoft Windows 7
  * Microsoft Windows Embedded Standard/Compact 7
  * Linux

* **System Monitoring & Management**

  * Wake-on-LAN
  * Keyboard-Power-on
  * Timer-Power-on
  * System Power Management
  * AC power failure recovery
  * Watchdog Timer

* **Operating Conditions**

  * Operating Temperature: 0°C ~60°C
  * Operating Humidity: 0% ~ 95% (relative humidity; non-condensing)

* **Form Factor**

  * Pico-ITX: 10 cm x 7.2 cm (12-layers)

* **Compliance**

  * CE
  * FCC
  * BSMI
  * RoHS

Layout Diagram
--------------

.. _figure-layout-top:
.. figure:: images/layout_top.*
   :align: center
   :alt: Layout diagram of the EPIA-P910 mainboard, top view

   Layout diagram of the EPIA-P910 mainboard, top view

.. _figure-layout-bottom:
.. figure:: images/layout_bottom.*
   :align: center
   :alt: Layout diagram of the EPIA-P910 mainboard, bottom view

   Layout diagram of the EPIA-P910 mainboard, bottom view

Layout diagram description table of the EPIA-P910 mainboard:

===== =============================
Item  Description
===== =============================
1     JM1: Clear CMOS jumper
2     CN3: High Speed Extension Slot
3     SATA connector 2
4     PWR2: SATA power connector
5     SATA connector 1
6     CN2: Audio+USB 2.0+Front Panel combination pin header
7     CN1: KB/MS/LPC/GPIO/SMBus combination pin header
8     LVDS1: LVDS connector
9     JM3: Panel power selector
10    JM2: Backlight power selector
11    FAN1: System/CPU fan
12    VIA QuadCore
13    VX11H chipset
14    PWR1: DC-in power connector
15    SODIMM1: DDR3 SODIMM slot
16    J1: SPI connector
17    BAT1: CMOS battery connector
===== =============================

Product Dimensions
------------------

.. _figure-mounting1:
.. figure:: images/mounting1.*
   :align: center
   :alt: Mounting holes and dimensions of the EPIA-P910

   Mounting holes and dimensions of the EPIA-P910

.. _figure-mounting2:
.. figure:: images/mounting2.*
   :align: center
   :alt: Mounting holes and dimensions of the EPIA-P910

   Mounting holes and dimensions of the EPIA-P910

Height Distribution
-------------------

.. _figure-height1:
.. figure:: images/height1.*
   :align: center
   :alt: Height distribution of the EPIA-P910 mainboard

   Height distribution of the EPIA-P910 mainboard

.. _figure-height2:
.. figure:: images/height2.*
   :align: center
   :alt: Height distribution of the EPIA-P910 mainboard

   Height distribution of the EPIA-P910 mainboard
