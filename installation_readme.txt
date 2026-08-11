<<<<<<< HEAD

Release Version: Alpha Release (MixOS Dev.)

Intel(R) Graphics Driver: 31.0.101.4509

Intel(R) Display Audio Driver:  10.26.0.12
Intel(R) Display Audio Driver:  10.27.0.12
Intel(R) Display Audio Driver:  11.1.0.20
Intel(R) Display Audio Driver:  11.2.0.10

Build Date: Aug 11, 2026

Operating Systems:
	Microsoft Windows* 10-64 - October 2018 Update (1809)(RS5)
	Microsoft Windows* 10-64 - May 2019 Update (1903)(19H1)
	Microsoft Windows* 10-64 - November 2019 Update (1909)(19H2)
	Microsoft Windows* 10-64 - October 2020 Update (20H2)
	Microsoft Windows* 10-64 - May 2021 Update (21H1)
	Microsoft Windows* 10-64 - November 2021 Update (21H2)
	Microsoft Windows* 11-64 - October 2021 Update (21H2)

	Microsoft Windows* 11-64 (22H2)
	Microsoft Windows* 11-64 (25H2)

Platforms:

	6th Gen Intel(R) Core(TM) processor family (Codename Skylake)

	7th Gen Intel(R) Core(TM) processor family (Codename Kaby Lake)

	8th Gen Intel(R) Core(TM) processor family (Codename Kaby Lake-R, Coffee Lake, Whiskey Lake)

	9th Gen Intel(R) Core(TM) processor family (Codename Coffee Lake-R)

	10th Gen Intel(R) Core(TM) processor family (Codename Comet Lake, Amber Lake, Ice Lake)

	Intel(R) Core(TM) Processor with Intel(R) Hybrid Technology (Codename Lakefield)

	Intel(R) Atom(R), Pentium(R) and Celeron(R) processor family (Codename Apollo Lake, Elkhart Lake)

	Intel(R) Pentium(R) and Celeron(R) processor family (Codename Gemini Lake, Jasper Lake)

DISCLAIMER: Intel is making no claims of usability, efficacy or warranty.  The INTEL SOFTWARE LICENSE AGREEMENT contained herein completely defines the license and use of this software.
This document contains information on products in the design phase of development. The information here is subject to change without notice. Do not finalize a design with this information.

CONTENTS OF THIS DOCUMENT
I.		System Requirements
II.		Localized Language Abbreviations
III.	Installing the Software
IV.		Verifying Installation of the Software
V.		Identifying the Software Version Number
VI.		Installation Switches
VII.	Uninstalling the Software

I.   SYSTEM REQUIREMENTS
1.  The system must contain one of the Intel chipsets/processors in the list of above Platforms and be running on one of the above listed Operating Systems.
2.  The software should be installed on systems with at least 4 GB of system memory.
3.  There should be sufficient hard disk space in the <TEMP> directory on the system in order to install this software.

II.   LOCALIZED LANGUAGE ABBREVIATIONS
The following list contains the hexadecimal key of all
languages into which the driver has been localized. You may
have to refer to this section while using this document.

ara – Arabic (Saudi Arabia)
cht – Chinese (Simplified)
cht – Chinese (Traditional)
hrv - Croatian
cys - Czech
dan - Danish
nld - Dutch
enu - English (US)
fin - Finnish
fra-  French
deu - German
ell - Greek
heb - Hebrew
hun - Hungarian
ita - Italian
jpn - Japanese
kor - Korean
nor – Norwegian (Bokmal)
plk - Polish
ptg - Portuguese (Brazilian)
ptb - Portuguese
rom - Romanian
rus-  Russian
SKY - Slovak
SLV - Slovenian
Esp - Spanish
Sve - Swedish
Tha - Thai
Trk - Turkish

III.   INSTALLING THE SOFTWARE
General Installation Notes:
1.  The operating system must be installed prior to the installation of the
    driver.
2.  This installation procedure is specific only to the version of driver
    and installation file included in this release.
3.  This procedure assumes that all of the software associated with this
    release is located in the same directory.
4.	When updating from a non-DCH driver to a DCH driver, Have-Disk
	installation is not recommended, and may leave the system in an unstable state.
	If you are unsure if your drivers are DCH or non, we recommend only
	using igxpin.exe/installer.exe or the extractable EXE to install the driver.

INSTALLATION INSTRUCTIONS
------------------------------------------------------------------
To install from a Web download, you will download either a .zip file or an
.exe file.
a. If it is a .zip file, double-click on the file you downloaded and choose
   "Extract all files". Browse to a destination folder and choose "Extract".
b. If it is an .exe file, double-click on the file you downloaded and the installer splash screen with pop-up.

------------------------------------------------------------------
  Microsoft Windows* "igxpin.exe" Installation
------------------------------------------------------------------
1. Locate the hard drive directory where the driver files are stored
   using the browser or the Explore feature of Windows*.
2. From this directory, double-click the "igxpin.exe" file.
3. The first dialog of the installation user interface will appear.
4. Click "Next" to continue.
5. Read the License Agreement and, if you agree with the terms,
   click "Yes" to proceed.
6. Review the Readme File information and click "Next" to proceed.
7. When the "Setup Progress" is complete, click "Next" to proceed.
8. When the "Setup is Complete" screen appears, click "Finish" to
   complete the installation. It's recommended to reboot immediately to restart key services, but it is not a requirement.
   
------------------------------------------------------------------
  Microsoft Windows* "installer.exe" Installation
------------------------------------------------------------------
1. Locate the hard drive directory where the driver files are stored
   using the browser or the Explore feature of Windows*.
2. From this directory, double-click the "installer.exe" file.
3. The first dialog of the installation user interface will appear.
4. Click "Next" to continue.
5. Read the License Agreement and, if you agree with the terms,
   click "Next" to proceed.
6. When the "Pre-install" is complete, click "Start" to proceed.
7. When the "Installation is Complete" screen appears, click "Finish" to
   complete the installation. "Reboot" may be required depending on the
   installation scenario, which is determined by the Windows* Installer.

To determine if the driver has been loaded correctly, refer to the section below.

IV.   VERIFYING INSTALLATION OF THE SOFTWARE
1.  Right click "Start", select "Device Manager".
2.  In the "User Account Control" window, click "Yes".
3.  For Intel(R) Graphics Driver, expand "Display adapters". The Intel(R) Graphics Driver should
    be listed. If not, the driver is not installed correctly.
4.  For Intel(R) Display Audio Driver, expand "Sound, video and game controllers". The "Intel(R) Display
    Audio" driver should be listed and should not show a yellow bang.
    If not, the driver is not installed correctly.

To check the version of the driver, refer to the section below.

V.   IDENTIFYING THE SOFTWARE VERSION NUMBER
Device Manager:
1.  Right click "Start", select "Device Manager".
2.  In the "User Account Control" window, click "Yes".
3.  For Intel(R) Graphics Driver, expand "Display adapters" and double-click the graphics controller. In the "Driver" tab, note the Driver Version.
4.  For Intel(R) Display Audio Driver, expand "Sound, video and game controllers" and double-click "Intel(R) Display Audio". In the "Driver" tab, click "Driver Details" and the function driver (IntcDAud.sys) version should be listed on this screen.

Intel(R) Graphics Command Center:
1.  Click on "Start", search for "Graphics Command Center" and launch the application.
2.  Select the "System" tab on the lefthand side.
3.  Choose the "Driver" header and note the driver version under Graphics Driver.

VI.   INSTALLATION SWITCHES
The switches in the igxpin.exe/installer.exe file will have the following syntax.
Switches are not case-sensitive and may be specified in any order
(except for the -s switch). Switches must be separated by spaces.
SETUP [-b] [-overwrite] [-l<LCID>] [-s] [-report <path>]

GFX-INSTALLATION CUSTOM SWITCHES
-b Forces a system reboot after the installation completes.
In non-silent mode, the absence of this switch will prompt
the user to reboot. In silent mode, the absence of this
switch forces the igxpin.exe/installer.exe to complete without rebooting
(the user must manually reboot to conclude the installation
process).

-overwrite Installs the Intel(R) Graphics Driver regardless of
the version of previously installed driver. In non-silent mode,
the absence of this switch will prompt the user to confirm
overwrite of a newer Intel(R) Graphics Driver. In silent mode,
the absence of this switch means that the installation will
abort any attempts to regress the revision of the Intel(R) Graphics
driver.

-l<LCID> Specifies the language used in the installation user
interface. Without this switch, the installation user interface
will be shown in the Display language of the OS by default.
Hexadecimal values for the supported languages can be found in
the localized language abbreviations section of this readme.

-s Runs in silent mode. The absence of this switch causes
the installation to be performed in verbose mode.

-report <path> Specifies an alternate location for the log file
created by a silent installation. By default, the log file is
created and stored during a silent installation under <root
directory>\Intel\Logs directory as IntelGFX.log
(<WINDIR>\Temp\IntelGFX.log).

VII.   UNINSTALLING THE SOFTWARE
NOTE: This procedure assumes the above installation process
was successful. This uninstallation procedure is specific
only to the version of the driver and installation files
included in this package.

1.  Right click "Start", select "Device Manager".
2.  In the "User Account Control" window, click "Yes".
3.  For Intel(R) Graphics Driver, expand "Display adapters".
4.  Right click the Intel(R) Graphics Driver and select "Uninstall device".
5.  Select the "Delete the driver software for this device" check box and click "Uninstall".
6.  For Intel(R) Display Audio Driver, expand "Sound, video and game controllers".
7.  Right click the Intel(R) Display Audio Driver and select "Uninstall device".
8.  Select the "Delete the driver software for this device" check box and click "Uninstall".
=======

Release Version: Alpha Release (MixOS Dev.)

Intel(R) Graphics Driver: 31.0.101.4509

Intel(R) Display Audio Driver:  10.26.0.12
Intel(R) Display Audio Driver:  10.27.0.12
Intel(R) Display Audio Driver:  11.1.0.20
Intel(R) Display Audio Driver:  11.2.0.10

Build Date: Aug 11, 2026

Operating Systems:
	Microsoft Windows* 10-64 - October 2018 Update (1809)(RS5)
	Microsoft Windows* 10-64 - May 2019 Update (1903)(19H1)
	Microsoft Windows* 10-64 - November 2019 Update (1909)(19H2)
	Microsoft Windows* 10-64 - October 2020 Update (20H2)
	Microsoft Windows* 10-64 - May 2021 Update (21H1)
	Microsoft Windows* 10-64 - November 2021 Update (21H2)
	Microsoft Windows* 11-64 - October 2021 Update (21H2)

	Microsoft Windows* 11-64 (22H2)
	Microsoft Windows* 11-64 (25H2)

Platforms:

	6th Gen Intel(R) Core(TM) processor family (Codename Skylake)

	7th Gen Intel(R) Core(TM) processor family (Codename Kaby Lake)

	8th Gen Intel(R) Core(TM) processor family (Codename Kaby Lake-R, Coffee Lake, Whiskey Lake)

	9th Gen Intel(R) Core(TM) processor family (Codename Coffee Lake-R)

	10th Gen Intel(R) Core(TM) processor family (Codename Comet Lake, Amber Lake, Ice Lake)

	Intel(R) Core(TM) Processor with Intel(R) Hybrid Technology (Codename Lakefield)

	Intel(R) Atom(R), Pentium(R) and Celeron(R) processor family (Codename Apollo Lake, Elkhart Lake)

	Intel(R) Pentium(R) and Celeron(R) processor family (Codename Gemini Lake, Jasper Lake)

DISCLAIMER: Intel is making no claims of usability, efficacy or warranty.  The INTEL SOFTWARE LICENSE AGREEMENT contained herein completely defines the license and use of this software.
This document contains information on products in the design phase of development. The information here is subject to change without notice. Do not finalize a design with this information.

CONTENTS OF THIS DOCUMENT
I.		System Requirements
II.		Localized Language Abbreviations
III.	Installing the Software
IV.		Verifying Installation of the Software
V.		Identifying the Software Version Number
VI.		Installation Switches
VII.	Uninstalling the Software

I.   SYSTEM REQUIREMENTS
1.  The system must contain one of the Intel chipsets/processors in the list of above Platforms and be running on one of the above listed Operating Systems.
2.  The software should be installed on systems with at least 4 GB of system memory.
3.  There should be sufficient hard disk space in the <TEMP> directory on the system in order to install this software.

II.   LOCALIZED LANGUAGE ABBREVIATIONS
The following list contains the hexadecimal key of all
languages into which the driver has been localized. You may
have to refer to this section while using this document.

ara – Arabic (Saudi Arabia)
cht – Chinese (Simplified)
cht – Chinese (Traditional)
hrv - Croatian
cys - Czech
dan - Danish
nld - Dutch
enu - English (US)
fin - Finnish
fra-  French
deu - German
ell - Greek
heb - Hebrew
hun - Hungarian
ita - Italian
jpn - Japanese
kor - Korean
nor – Norwegian (Bokmal)
plk - Polish
ptg - Portuguese (Brazilian)
ptb - Portuguese
rom - Romanian
rus-  Russian
SKY - Slovak
SLV - Slovenian
Esp - Spanish
Sve - Swedish
Tha - Thai
Trk - Turkish

III.   INSTALLING THE SOFTWARE
General Installation Notes:
1.  The operating system must be installed prior to the installation of the
    driver.
2.  This installation procedure is specific only to the version of driver
    and installation file included in this release.
3.  This procedure assumes that all of the software associated with this
    release is located in the same directory.
4.	When updating from a non-DCH driver to a DCH driver, Have-Disk
	installation is not recommended, and may leave the system in an unstable state.
	If you are unsure if your drivers are DCH or non, we recommend only
	using igxpin.exe/installer.exe or the extractable EXE to install the driver.

INSTALLATION INSTRUCTIONS
------------------------------------------------------------------
To install from a Web download, you will download either a .zip file or an
.exe file.
a. If it is a .zip file, double-click on the file you downloaded and choose
   "Extract all files". Browse to a destination folder and choose "Extract".
b. If it is an .exe file, double-click on the file you downloaded and the installer splash screen with pop-up.

------------------------------------------------------------------
  Microsoft Windows* "igxpin.exe" Installation
------------------------------------------------------------------
1. Locate the hard drive directory where the driver files are stored
   using the browser or the Explore feature of Windows*.
2. From this directory, double-click the "igxpin.exe" file.
3. The first dialog of the installation user interface will appear.
4. Click "Next" to continue.
5. Read the License Agreement and, if you agree with the terms,
   click "Yes" to proceed.
6. Review the Readme File information and click "Next" to proceed.
7. When the "Setup Progress" is complete, click "Next" to proceed.
8. When the "Setup is Complete" screen appears, click "Finish" to
   complete the installation. It's recommended to reboot immediately to restart key services, but it is not a requirement.
   
------------------------------------------------------------------
  Microsoft Windows* "installer.exe" Installation
------------------------------------------------------------------
1. Locate the hard drive directory where the driver files are stored
   using the browser or the Explore feature of Windows*.
2. From this directory, double-click the "installer.exe" file.
3. The first dialog of the installation user interface will appear.
4. Click "Next" to continue.
5. Read the License Agreement and, if you agree with the terms,
   click "Next" to proceed.
6. When the "Pre-install" is complete, click "Start" to proceed.
7. When the "Installation is Complete" screen appears, click "Finish" to
   complete the installation. "Reboot" may be required depending on the
   installation scenario, which is determined by the Windows* Installer.

To determine if the driver has been loaded correctly, refer to the section below.

IV.   VERIFYING INSTALLATION OF THE SOFTWARE
1.  Right click "Start", select "Device Manager".
2.  In the "User Account Control" window, click "Yes".
3.  For Intel(R) Graphics Driver, expand "Display adapters". The Intel(R) Graphics Driver should
    be listed. If not, the driver is not installed correctly.
4.  For Intel(R) Display Audio Driver, expand "Sound, video and game controllers". The "Intel(R) Display
    Audio" driver should be listed and should not show a yellow bang.
    If not, the driver is not installed correctly.

To check the version of the driver, refer to the section below.

V.   IDENTIFYING THE SOFTWARE VERSION NUMBER
Device Manager:
1.  Right click "Start", select "Device Manager".
2.  In the "User Account Control" window, click "Yes".
3.  For Intel(R) Graphics Driver, expand "Display adapters" and double-click the graphics controller. In the "Driver" tab, note the Driver Version.
4.  For Intel(R) Display Audio Driver, expand "Sound, video and game controllers" and double-click "Intel(R) Display Audio". In the "Driver" tab, click "Driver Details" and the function driver (IntcDAud.sys) version should be listed on this screen.

Intel(R) Graphics Command Center:
1.  Click on "Start", search for "Graphics Command Center" and launch the application.
2.  Select the "System" tab on the lefthand side.
3.  Choose the "Driver" header and note the driver version under Graphics Driver.

VI.   INSTALLATION SWITCHES
The switches in the igxpin.exe/installer.exe file will have the following syntax.
Switches are not case-sensitive and may be specified in any order
(except for the -s switch). Switches must be separated by spaces.
SETUP [-b] [-overwrite] [-l<LCID>] [-s] [-report <path>]

GFX-INSTALLATION CUSTOM SWITCHES
-b Forces a system reboot after the installation completes.
In non-silent mode, the absence of this switch will prompt
the user to reboot. In silent mode, the absence of this
switch forces the igxpin.exe/installer.exe to complete without rebooting
(the user must manually reboot to conclude the installation
process).

-overwrite Installs the Intel(R) Graphics Driver regardless of
the version of previously installed driver. In non-silent mode,
the absence of this switch will prompt the user to confirm
overwrite of a newer Intel(R) Graphics Driver. In silent mode,
the absence of this switch means that the installation will
abort any attempts to regress the revision of the Intel(R) Graphics
driver.

-l<LCID> Specifies the language used in the installation user
interface. Without this switch, the installation user interface
will be shown in the Display language of the OS by default.
Hexadecimal values for the supported languages can be found in
the localized language abbreviations section of this readme.

-s Runs in silent mode. The absence of this switch causes
the installation to be performed in verbose mode.

-report <path> Specifies an alternate location for the log file
created by a silent installation. By default, the log file is
created and stored during a silent installation under <root
directory>\Intel\Logs directory as IntelGFX.log
(<WINDIR>\Temp\IntelGFX.log).

VII.   UNINSTALLING THE SOFTWARE
NOTE: This procedure assumes the above installation process
was successful. This uninstallation procedure is specific
only to the version of the driver and installation files
included in this package.

1.  Right click "Start", select "Device Manager".
2.  In the "User Account Control" window, click "Yes".
3.  For Intel(R) Graphics Driver, expand "Display adapters".
4.  Right click the Intel(R) Graphics Driver and select "Uninstall device".
5.  Select the "Delete the driver software for this device" check box and click "Uninstall".
6.  For Intel(R) Display Audio Driver, expand "Sound, video and game controllers".
7.  Right click the Intel(R) Display Audio Driver and select "Uninstall device".
8.  Select the "Delete the driver software for this device" check box and click "Uninstall".
>>>>>>> 3e72ffe0443bc9e44c08c3e90727aeb555da7d57
