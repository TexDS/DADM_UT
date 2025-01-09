# About

DADM_UT is based on the [free Excel add-ins](https://host.kelley.iu.edu/albrightbooks/Free_downloads.htm) for the Business Analytics textbook by Albright and Winston. 

The DADM_UT add-in is independently maintained. It is provided for free and without warranty or active support. 

# User Guide

[Download the DADM_UT user guide and installation instructions](https://github.com/TexDS/DADM_UT/blob/main/DADM%20Guide.pdf)

[A page with helpful tips.](https://github.com/TexDS/DADM_UT/blob/main/tips.md)

# Download

[Download DADM_UT](https://github.com/TexDS/DADM_UT/releases/download/v3.3.0/DADM_UT.xlam)

NOTE: This add-in works on both Windows and Mac with the desktop Excel application. It does **not** work with the online Excel web-app.


# Installation

## Install on Windows

### Unblock the add-in (.xlam) file

1. Go to the folder where you saved the add-in
2. Right click on the add-in file and click Properties
3. Check the box beside “Unblock” at the bottom and click Apply, then click OK

      Note: If you do not see the checkbox to unblock, close the Properties window, left click **once** on the file to ensure it is selected, then right click it and select Properties

### Load the add-in to Excel

1. Open Excel and a new workbook
2. Click “File” on the menu ribbon
3. On the left-side menu, click “Options” near the bottom (if you don’t see it, click “More...” at the bottom of that menu)
4. In the new window, click “Add-ins” near the bottom of the left-side menu
5. At the bottom of this window, ensure that “Excel Add-ins” is selected in the drop- down menu and click “Go...”
6. In the Add-ins window, click “Browse...” and navigate to where you saved the DADM add-in file
7. Select the add-in file and click “OK” and click “OK” again to close the add-in window

## Install on Mac

1. Open Excel and a new workbook b) Click “Tools” on the Mac menu bar
2. On the drop-down menu, click “Excel Add-ins...”
3. In the new window, click “Browse...”
4. Navigate to where you saved the DADM add-in file and click on it to select it
5. Click “Open”
6. Click “OK” in the add-ins window

## Common Problems
### Troubleshoot Installation on Windows

If you have correctly installed DADM_UT and enabled macros, but you have any of these problems:

- get a warning message, "File couldn't open in protected view," when opening Excel
- DADM menu buttons don't work, try the following:
- get the #NAME! error for probability functions

You need to manually add the location of wherever the DADM_UT file was downloaded into the trust center. It seems to mostly be a problem on Windows 11, but not earlier Windows versions.

First, delete the DADM_UT file and re-download it (make sure to right click on the file, go to Properties, and check the box to unblock the file, if that box is there).

Then in Excel go to:

1. File
2. Options
3. Trust Center (left hand side menu)
4. Then click Trust Center Settings
5. go to Trusted Locations
6. Add new location..
7. then Browse or manually type the path wherever the DADM file was loaded
8. then click OK and OK again to get out of the options.

### Troubleshoot Removing DADM on Windows

Sometimes after removing an add in, Excel still looks for the add in when you open Excel and gives a "file can't be found" error message.

First you will want to note the file path that Excel thinks the add-in should be located in and the name of the add-in file. Once you know where that folder is located and the name of the add-in, proceed to do the following:

1. Create a new Excel file
2. Save the file with the following conditions:
      - Use the Add-in name
      - Use the Excel file extension “.xlam” (if it is an older add-in it might need to be “.xla”)
      - Save to the same folder path
3. Once you have saved this new faux add-in file, close down Excel
4. Reopen Excel and hopefully you won’t receive the error message
5. Go into your Excel Add-ins dialog box and check the add-in and hit Ok
6. Go back into you Excel Add-ins dialog box and uncheck the add-in and hit OK
7. Close out of Excel

### Troubleshoot Installation on Mac

If you have a Mac and are having a problem with Excel crashing when you try to run a simulation with DADM, you might need to open Excel with Rosetta, a software used on Macs with the new M1 chip.

1. Close any Microsoft apps (Excel, PowerPoint, etc.)
2. in Finder, navigate to where the Excel app is (most likely in your Applications folder)
3. Right-click on the Excel app and select "Get Info"
4. Check the box for "Open using Rosetta" (if it is there)
5. Then open Excel again and try running a simulation.
6. See here for instructions with screenshots: https://www.ithinkdiff.com/open-apps-using-rosetta-mac-m1/

If DADM has been working but suddenly starts crashing or giving errors like this:   

![image](https://github.com/user-attachments/assets/81cbd3ed-1b34-4251-9d49-c5ec00e0bb44)

You might just need to restart Excel and/or your computer.
Note that to restart Excel on a Mac, you need to quit the Excel application (not just close all open Excel windows). When you have an Excel window selected, click "Excel" at the menu bar at the top of your screen and click "Quit Excel" to fully close the app. Or, you can right click on the Excel app icon in the dock (at the bottom of the screen) and click Quit.

# Tutorials

[Basic Monte Carlo Simulation](https://youtu.be/F4V6cRiI1tE)

[Decision Variables in DADM_UT](https://www.youtube.com/watch?v=vMy46u2ovEQ)

[Building Decision Trees](https://youtu.be/O-ZQ8p5cSHA)


