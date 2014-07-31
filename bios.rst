.. _bios:

BIOS Setup Utility
==================

Entering the BIOS Setup Utility
-------------------------------

Power on the computer and press Delete during the beginning of the boot
sequence to enter the BIOS Setup Utility. If the entry point has passed, restart
the system and try again.

Control Keys
------------

========== ===============================================================
Key        Function
========== ===============================================================
Up         Move up one row
Down       Move down one row
Left       Move to the left in the navigation bar
Right      Move to the right in the navigation bar
Enter      Access the highlighted item / Select the item
Esc        Jumps to the Exit screen or returns to the previous screen
\+ [#f1]_   Increase the numeric value
\- [#f1]_   Decrease the numeric value
F1         General help [#f2]_
F2         Previous value
F3         Load optimized defaults
F4         Save all the changes and exit
========== ===============================================================

.. rubric:: Footnotes
.. [#f1] Must be pressed using the 10-key pad.
.. [#f2] The General help contents are only for the Status Page and Option Page setup menus.

Getting Help
------------

The BIOS Setup Utility provides a **General Help** screen. This screen can be
accessed at any time by pressing **F1**. The help screen displays the keys for
using and navigating the BIOS Setup Utility. Press **Esc** to exit the help screen.

System Overview
---------------

The System Overview screen is the default screen that is shown when the
BIOS Setup Utility is launched. This screen can be accessed by traversing the
navigation bar to the "Main" label.

.. _figure-bios01:
.. figure:: images/bios01.*
   :align: center
   :alt: Illustration of the Main menu screen

   Illustration of the Main menu screen

BIOS Information
^^^^^^^^^^^^^^^^

The content in this section of the screen shows the information about the
vendor, the Core version, UEFI specification version, the project version and
date & time of the project build.

Memory Information
^^^^^^^^^^^^^^^^^^

This section shows the amount of memory that is installed on the hardware
platform.

System Language
^^^^^^^^^^^^^^^

This option allows the user to configure the language that the user wants to
use.

System Date
^^^^^^^^^^^

This section shows the current system date. Press **Tab** to traverse right and
**Shift+Tab** to traverse left through the month, day, and year segments. The +
and - keys on the number pad can be used to change the values. The weekday
name is automatically updated when the date is altered. The date format is
[Weekday, Month, Day, Year].

System Time
^^^^^^^^^^^

This section shows the current system time. Press **Tab** to traverse right and
**Shift+Tab** to traverse left through the hour, minute, and second segments. The
+ and - keys on the number pad can be used to change the values. The time
format is [Hour : Minute : Second].

Advanced Settings
-----------------

The Advanced Settings screen shows a list of categories that can provide
access to a sub-screen. Sub-screen links can be identified by the preceding
right-facing arrowhead.

.. _figure-bios02:
.. figure:: images/bios02.*
   :align: center
   :alt: Illustration of the Advanced Settings screen

   Illustration of the Advanced Settings screen

The Advanced Settings screen contains the following links:

* ACPI Settings
* S5 RTC Wake Settings
* CPU Configuration
* SATA Configuration
* F81801 H/W Monitor
* Clock Generator Configuration
* Onboard Configuration

ACPI Settings
^^^^^^^^^^^^^

ACPI grants the operating system direct control over system power
management. The ACPI Configuration screen can be used to set a number of
power management related functions.

.. _figure-bios03:
.. figure:: images/bios03.*
   :align: center
   :alt: Illustration of the ACPI Settings screen

   Illustration of the ACPI Settings screen

Enable Hibernation
""""""""""""""""""

Enable/disable system ability to Hibernate.

ACPI Sleep State
""""""""""""""""

Select the highest ACPI sleep state the system will enter when the SUSPEND
button is selected. Available options are:

 * Suspend Disabled
 * S1(CPU Stop Clock)
 * S3 (Suspend to RAM)
 * Both S1 and S3 available for OS to choose.

S5 RTC Wake Settings
^^^^^^^^^^^^^^^^^^^^

.. _figure-bios04:
.. figure:: images/bios04.*
   :align: center
   :alt: Illustration of the S5 RTC Wake Settings screen

   Illustration of the S5 RTC Wake Settings screen

Wake system with Fixed Time
"""""""""""""""""""""""""""

Enable or disable system wake on alarm event. When enabled, system will
wake on the hr:min:sec specified.

Wake system with Dynamic Time
"""""""""""""""""""""""""""""

Enable or disable Wake system with Dynamic Time.

CPU Configuration
^^^^^^^^^^^^^^^^^

The CPU Configuration screen shows detailed information about the built-in
processor. In addition to the processor information, the thermal controls can
be set.

.. _figure-bios05:
.. figure:: images/bios05.*
   :align: center
   :alt: Illustration of CPU Configuration screen

   Illustration of CPU Configuration screen

TM3
"""
The TM3 Function has two settings: Disabled and Enabled. When the setting is
changed to “Disabled”, the CPU’s built-in thermal sensor will not function.
When the setting is changed to “Enabled”, the thermal sensor will
automatically adjust the CPU ratio and V CORE to prevent the CPU from
overheating.

SATA Configuration
^^^^^^^^^^^^^^^^^^

The SATA Configuration screen allows the user to view and configure the
settings of the SATA configuration settings.

.. _figure-bios06:
.. figure:: images/bios06.*
   :align: center
   :alt: Illustration of SATA Configuration screen

   Illustration of SATA Configuration screen

SATA Mode
"""""""""

This option allows the user to manually configure SATA controller for a
particular mode.

* **IDE Mode**: Set this value to change the SATA to IDE mode.
* **AHCI Mode**: Set this value to change the SATA to AHCI mode.

PC Health Status
^^^^^^^^^^^^^^^^

The PC Health Status screen has no editable fields. The system temperature is
taken from an optional sensor that is connected to the **J5** pin header.

.. _figure-bios07:
.. figure:: images/bios07.*
   :align: center
   :alt: Illustration of PC Health Status screen

   Illustration of PC Health Status screen

Fan Turbo Mode
""""""""""""""

This option allows the user to Enable or Disable Fan Turbo Mode.

Clock Generator Configuration
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The Clock Generator Configuration screen enables access to the Spread
Spectrum Setting feature.

.. _figure-bios08:
.. figure:: images/bios08.*
   :align: center
   :alt: Illustration of Clock Generator Configuration screen

   Illustration of Clock Generator Configuration screen

CPU Spread Spectrum
"""""""""""""""""""

The Spread Spectrum Setting feature enables the BIOS to modulate the clock
frequencies originating from the mainboard. The settings are in percentages of
modulation. Higher percentages result in greater modulation of clock
frequencies. This feature has 3 options: Disable, +-0.25% and -0.5%.

PCIe Spread Spectrum
""""""""""""""""""""

Select PCIe Spread Spectrum. This feature has 2 options: Disable and -0.5%.

OnBoard Device Configuration
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The OnBoard Device Configuration screen has the following features.

.. _figure-bios09:
.. figure:: images/bios09.*
   :align: center
   :alt: Illustration of OnBoard Device Configuration screen

   Illustration of OnBoard Device Configuration screen

OnBoard LAN Enable
""""""""""""""""""

The OnBoard LAN Enable feature determines whether the onboard LAN
controller will be used or not.

EuP/ErP Lot6 support
""""""""""""""""""""

The EuP/ErP Lot6 Support feature enables the BIOS to reduce the power draw
to less than 1W when the system is in standby mode. This feature has two
options: enabled and disabled.

S5 Wakeup On LAN
""""""""""""""""

The S5 Wakeup On LAN feature enables the BIOS to allow remote wake-up
from the S5 power off state through the PCI bus.

1CH LVDS Backlight Control
""""""""""""""""""""""""""

**Backlight Control**

The Backlight Control feature control by VX11H enables the user to control
the brightness of the 1CH LVDS backlight. This feature has six options.

**Level**
0%, 20%, 40%, 60%, 80% and 100%.

2CH LVDS Backlight Control
""""""""""""""""""""""""""

**Backlight Control**

The Backlight Control feature control by VX11H enables the user to control
the brightness of the 2CH LVDS backlight. This feature has six options.

**Level**

0%, 20%, 40%, 60%, 80% and 100%.

Chipset Settings
----------------

The Chipset Settings screen shows a list of categories that can provide access
to a sub-screen. Sub-screen links can be identified by the preceding right-
facing arrowhead.

.. _figure-bios10:
.. figure:: images/bios10.*
   :align: center
   :alt: Illustration of Chipset Settings screen

   Illustration of Chipset Settings screen

The Chipset Settings screen contains the following links:

* DRAM Configuration
* Video Configuration
* PMU-ACPI Configuration
* SDIO_CR Configuration
* Others Configuration

DRAM Configuration
^^^^^^^^^^^^^^^^^^

The DRAM Configuration screen has two features for controlling the system
DRAM. All other DRAM features are automated and cannot be accessed.

.. _figure-bios11:
.. figure:: images/bios11.*
   :align: center
   :alt: Illustration of DRAM Configuration screen

   Illustration of DRAM Configuration screen

DRAM Clock
""""""""""

The DRAM Clock option enables the user to determine how the BIOS handles
the memory clock frequency. The memory clock can either be dynamic or
static. This feature has eleven options.

**By SPD**

By SPD option enables the BIOS to select a compatible clock frequency for the installed memory.

**400 MHz**

The 400 MHz option forces the BIOS to be fixed at 800 MHz for DDR3 memory modules.

**533 MHz**

The 533 MHz option forces the BIOS to be fixed at 1066 MHz for DDR3 memory modules.

**566 MHz**

The 566 MHz option forces the BIOS to be fixed at 1132 MHz for DDR3 memory modules.

**600 MHz**

The 600 MHz option forces the BIOS to be fixed at 1200 MHz for DDR3 memory modules.

**633 MHz**

The 633 MHz option forces the BIOS to be fixed at 1266 MHz for DDR3 memory modules.

**667 MHz**

The 667 MHz option forces the BIOS to be fixed at 1334 MHz for DDR3 memory modules.

VGA Share Memory (Frame Buffer)
"""""""""""""""""""""""""""""""

The VGA Share Memory feature enables the user to choose the amount of the
system memory to reserve for use by the integrated graphics controller. The
selections of memory amount that can be reserved are 256MB and 512MB.

Video Configuration
^^^^^^^^^^^^^^^^^^^

The Video Configuration screen has features for controlling the integrated
graphics controller in the VX11H chipset.

.. _figure-bios12:
.. figure:: images/bios12.*
   :align: center
   :alt: Illustration of Video Configuration screen

   Illustration of Video Configuration screen

Select Display Device Control
"""""""""""""""""""""""""""""

Available selections are: Auto and Manual.

Select Display Device 1 and 2
"""""""""""""""""""""""""""""

The Select Display Device feature enables the user to choose a specific
display interface. This feature has four options: CRT, LCD, LCD2 and HDMI. If
both Select Display Device 1 and Select Display Device 2 are set to the same
interface, then any display device connected to the other interface will not
function. For example, if both Select Display 1 and 2 are set to CRT, then no
data will be sent to the HDMI, LCD and LCD2 port.

Panel Type
""""""""""

The Panel Type feature enables the user to specify the resolution of the display
being used with the system. The panel types are predefined in the VGA VBIOS.

=========== =============== =========== ===============
Panel Type  Resolution      Panel Type  Resolution
=========== =============== =========== ===============
00          640 x 480       08          800 x 480
01          800 x 600       09          1024 x 600
02          1024 x 768      10          1366 x 768
03          1280 x 768      11          1600 x 1200
04          1280 x 1024     12          1680 x 1050
05          1400 x 1050     13          1920 x 1200
06          1440 x 900      14          1920 x 1080
07          1280 x 800      15          1024 x 576
=========== =============== =========== ===============

Panel Type2
"""""""""""
The Panel Type feature enables the user to specify the resolution of display 2
being used with the system. The panel types are predefined in the VGA VBIOS.

=========== =============== =========== ===============
Panel Type  Resolution      Panel Type  Resolution
=========== =============== =========== ===============
00          640 x 480       08          800 x 480
01          800 x 600       09          1024 x 600
02          1024 x 768      10          1366 x 768
03          1280 x 768      11          1600 x 1200
04          1280 x 1024     12          1680 x 1050
05          1400 x 1050     13          1920 x 1200
06          1440 x 900      14          1920 x 1080
07          1280 x 800      15          1024 x 576
=========== =============== =========== ===============

PMU_ACPI Configuration
^^^^^^^^^^^^^^^^^^^^^^

The PMU_ACPI Configuration screen can be used to set a number of power
management related functions.

.. _figure-bios13:
.. figure:: images/bios13.*
   :align: center
   :alt: Illustration of PMU_ACPI Configuration screen

   Illustration of PMU_ACPI Configuration screen

Other Control
"""""""""""""

.. _figure-bios14:
.. figure:: images/bios14.*
   :align: center
   :alt: Illustration of Other Control screen

   Illustration of Other Control screen

**AC Loss Auto-restart**

AC Loss Auto-restart defines how the system will respond after AC power has
been interrupted while the system is on. There are three options.

*Power Off*

The Power Off option keeps the system in an off state until the power button
is pressed again.

*Power On*

The Power On option restarts the system when the power has returned.

*Last State*

The Last State option restores the system to its previous state when the power
was interrupted.

**USB S4 WakeUp**

The USB S4 WakeUp enables the system to resume through the USB device
port from S4 state. There are two options: "Enabled" or “Disabled".

SDIO_CR Configuration
^^^^^^^^^^^^^^^^^^^^^

The SDIO_CR Configuration screen can be used to set SDIO_CR configuration
parameters.

.. _figure-bios15:
.. figure:: images/bios15.*
   :align: center
   :alt: Illustration of SDIO_CR Configuration screen

   Illustration of SDIO_CR Configuration screen

SDIO Host Controller
""""""""""""""""""""

Available selections are: Enabled and Disabled.

SDIO Specification Ver3.0 Support
"""""""""""""""""""""""""""""""""

Available selections are: Enabled and Disabled.

Voltage Support 1.8v
""""""""""""""""""""

Available selections are: Enabled and Disabled.

High Speed Support
""""""""""""""""""

Available selections are: Enabled and Disabled.

Driver Type Select
""""""""""""""""""

Available selections are: Type A, Type B, Type C and Type D.

SDR50 Support
"""""""""""""

Available selections are: Enabled and Disabled.

SDR104 Support
""""""""""""""

Available selections are: Enabled and Disabled.

DDR50 Support
"""""""""""""

Available selections are: Enabled and Disabled.

SDR50 Tuning Enable
"""""""""""""""""""

Available selections are: Enabled and Disabled.

Timer Count for Re-Tuning
"""""""""""""""""""""""""

Available selections are:

* 1 second
* 2 seconds
* 4 seconds
* 8 seconds
* 16 seconds
* 32 seconds
* 64 seconds
* 120 seconds
* 256 seconds
* 512 seconds
* 1024 seconds
* get information from other source

Card Reader Host Controller 0
"""""""""""""""""""""""""""""

Available selections are: Enabled and Disabled.

Others Configuration
^^^^^^^^^^^^^^^^^^^^

The Others Configuration screen can be used to set Watchdog Timer
Configuration and Keyboard/Mouse Wakeup Configuration.

.. _figure-bios16:
.. figure:: images/bios16.*
   :align: center
   :alt: Illustration of Others Configuration screen

   Illustration of Others Configuration screen

WATCHDOG Timer Enable
"""""""""""""""""""""

When this feature is enabled, an embedded timing device automatically
prompts corrective action upon system malfunction detection.

Keyboard/Mouse Wakeup Control
"""""""""""""""""""""""""""""

When this feature is enabled, pressing any key of the keyboard or moving the
mouse can wake up the system from suspend.

Boot Settings
-------------

The Boot Settings screen has a single link that goes to the **Boot Configuration**
and **Boot Option Priorities** screens.

.. _figure-bios17:
.. figure:: images/bios17.*
   :align: center
   :alt: Illustration of Boot Settings screen

   Illustration of Boot Settings screen

Boot Configuration
^^^^^^^^^^^^^^^^^^

The Boot Settings Configuration screen has several features that can be run
during the system boot sequence.

Quiet Boot
""""""""""

The Quiet Boot feature hides all of the Power-on Self Test (POST) messages
during the boot sequence. Instead of the POST messages, the user will see an
OEM logo. This feature has two options: enabled and disabled.

Boot Option Priorities
^^^^^^^^^^^^^^^^^^^^^^

The Boot Option Priorities screen lists all bootable devices.

Launch PXE OpROM policy
"""""""""""""""""""""""

**Do not launch**

Prevent the option for Legacy Network Device.

**Legacy only**

Allow the option for Legacy Network Device.

Save & Exit
-----------

The Save & Exit Configuration screen has the following features:

.. _figure-bios18:
.. figure:: images/bios18.*
   :align: center
   :alt: Illustration of Save & Exit screen

   Illustration of Save & Exit screen

Save Changes and Exit
^^^^^^^^^^^^^^^^^^^^^

Save all changes to the BIOS and exit the BIOS Setup Utility. The “F10” hotkey
can also be used to trigger this command.

Discard Changes and Exit
^^^^^^^^^^^^^^^^^^^^^^^^

Exit the BIOS Setup Utility without saving any changes. The “Esc” hotkey can
also be used to trigger this command.

Save Changes and Reset
^^^^^^^^^^^^^^^^^^^^^^

Save all changes to the BIOS and reboot the system. The new system
configuration parameters will take effect.

Discard Changes and Reset
^^^^^^^^^^^^^^^^^^^^^^^^^

This command reverts all changes to the settings that were in place when the
BIOS Setup Utility was launched. The “F7” hotkey can also be used to trigger
this command.

Save Options
^^^^^^^^^^^^

Save Changes done so far to any of the setup options.

Save Changes
^^^^^^^^^^^^

Save system configuration and continue. For some of the options it required to
reset the system to take effect.

Discard Changes
^^^^^^^^^^^^^^^

Undo the previous changes.

Restore Defaults
^^^^^^^^^^^^^^^^

Restore default values for all setup options.
