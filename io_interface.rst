.. _io-interface:

I/O Interface
=============

The VIA EPIA-P910 has a wide selection of interfaces. It includes a selection of
frequently used ports as part of the external I/O coastline.

External I/O Ports
------------------

.. _figure-external-io:
.. figure:: images/external_io.*
   :align: center
   :alt: External I/O ports

   External I/O ports

Layout diagram description table of external I/O ports:

====== ===========================
Item   Description
====== ===========================
1      RJ1: Gigabit LAN port
2      USB1: USB 3.0 ports
3      USB2: USB 3.0 ports
4      HDMI1: Mini HDMI® port
5      VGA1: VGA port
====== ===========================

LAN port: Gigabit Ethernet
^^^^^^^^^^^^^^^^^^^^^^^^^^

The integrated 8-pin Gigabit Ethernet port is using an 8 Position 8 Contact
(8P8C) receptacle connector (commonly referred to as RJ45). The Gigabit
Ethernet ports are controlled by VIA Fast Ethernet controller. The pinout of
the Gigabit Ethernet port is shown below:

.. _figure-lan:
.. figure:: images/lan.*
   :align: center
   :alt: Gigabit Ethernet port pinout diagram

   Gigabit Ethernet port pinout diagram

Gigabit Ethernet port pinout:

==== =======================
Pin  Signal
==== =======================
1    Signal pair 1+
2    Signal pair 1-
3    Signal pair 2+
4    Signal pair 3+
5    Signal pair 3-
6    Signal pair 2-
7    Signal pair 4+
8    Signal pair 4-
==== =======================

The RJ-45 port has two individual LED indicators located on the front side to
show its Active/Link status and Speed status.

Gigabit Ethernet LED color definition:

================ ====================================================== ========================
State            Link LED (Left LED)                                    Active LED (Right LED)
================ ====================================================== ========================
Link Off         Off                                                    Off
Speed 10Mbit     The LED is always On in either Green or Orange colors  Flash in Yellow color
Speed 100Mbit    The LED is always On in Green color                    Flash in Yellow color
Speed 1000Mbit   The LED is always On in Orange color                   Flash in Yellow color
================ ====================================================== ========================

USB 3.0 Port
^^^^^^^^^^^^

The EPIA-P910 mainboard provides two USB 3.0 ports, also known as
SuperSpeed USB. The USB 3.0 port has a maximum data transfer rate up to 5
Gbps and offers a backwards compatible with previous USB 2.0 specifications.
The USB 3.0 ports are using the USB Type-A receptacle connector. The pinout
of the typical USB 3.0 port is shown below.

.. _figure-usb3:
.. figure:: images/usb3.*
   :align: center
   :alt: USB 3 .0 port pinout diagram

   USB 3 .0 port pinout diagram

USB 3.0 port pinout:

===== ========
Pin   Signal
===== ========
1     +5V
2     Data-
3     Data+
4     GND
5     Rx-
6     Rx+
7     GND
8     Tx-
9     Tx+
===== ========

Mini HDMI Port
^^^^^^^^^^^^^^

The integrated 19-pin HDMI® port uses an HDMI® Type C connector as
defined in the HDMI® specification. The HDMI® port is for connecting to
HDMI ® displays. The pinout of the Mini HDMI® port is shown below.

.. _figure-hdmi:
.. figure:: images/hdmi.*
   :align: center
   :alt: Mini HDMI® port pinout diagram

   Mini HDMI ® port pinout diagram

====== ========================= ====== ===================
Pin    Signal                    Pin    Signal
====== ========================= ====== ===================
1      TMDS Data2 Shield         2      TMDS Data2+
3      TMDS Data2-               4      TMDS Data1 Shield
5      TMDS Data1+               6      TMDS Data1–
7      TMDS Data0 Shield         8      TMDS Data0+
9      TMDS Data0-               10     TMDS Clock Shield
11     TMDS Clock+               12     TMDS Clock-
13     DDC/CEC Ground            14     CEC
15     SCL                       16     SDA
17     Reserved (N.C. on device) 18     +5V Power
19     Hot Plug Detect
====== ========================= ====== ===================

VGA Port
^^^^^^^^

The 15-pin VGA port uses a female DE-15 connector. The VGA port is for
connecting to analog displays. The pinout of the VGA port is shown below.

.. _figure-vga:
.. figure:: images/vga.*
   :align: center
   :alt: VGA port pinout diagram

   VGA port pinout diagram

VGA port pinout:

==== ========== ==== ========== 
Pin  Signal     Pin  Signal
==== ========== ==== ========== 
1    VGA-R      9    +5VCRT
2    VGA-G      10   Ground
3    VGA-B      11   NC
4    NC         12   VGA-SPD
5    Ground     13   VGA_HS
6    Ground     14   VGA_VS
7    Ground     15   VGA-SPCLK
8    Ground
==== ========== ==== ========== 
