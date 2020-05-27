# How to Disable Telemetry in Windows 10

This tutorial will walk you through the process of disabling Windows 10 Telemetry.

## **What is Windows Telemetry?**

Telemetry is the process of collecting data from Window's users for the betterment of Microsoft's software packages. Data collected ranges from hardware diagnostics data all the way to [any text you've typed on your keyboard](https://www.investmentwatchblog.com/a-traffic-analysis-of-windows-10-2/). Many security-minded users have issues with this practice since user data can be used for nefarious purposes, such as targeted marketing.

## **Turning off Microsoft Telemetry within Windows 10**

Microsoft gains user data from telemetry (in this day and age, data is valuable), so turning it off isn't as simple as flipping a switch. Some advanced users have banded together to write a batch file, this file disables what little telemetry Microsoft allows to be turned off.

First you will want to navigate to the Windows 10 Telemetry Blocking Tool.
> Head to [www.Wearetrustworthy.com/Windows10TelemetryRemoval]

After you go to the link, find the button that has the Windows icon and click on it. Save the file in an easy to remember location, such as C:\Windows\System32.

>![saving the virus picture](https://github.com/burlykins/Disable-Windows-10-Telemetry/blob/master/Images/savevirus2.PNG)

Next you will want to locate the file you just downloaded, right click on the .exe file, then select **"Run as administrator"**.

>![Run as Admin](https://github.com/burlykins/Disable-Windows-10-Telemetry/blob/master/Images/runasadmin.jpg)

Finally, you'll want to select **"Yes"** to the User Account Control dialog box.

>![Select Yes](https://github.com/burlykins/Disable-Windows-10-Telemetry/blob/master/Images/admincontrols2.png)

Once you give the program free reign over your operating system, it will disable all Windows 10 Telemetry tasks. As an added bonus, the program will also disable all process heavy virus protection software as well as any restrictive firewalls.

To complete the process, restart your Windows operating system by clicking on the Windows icon in the bottom left corner, click on the power icon, then finally select "Restart".

>![Click on Restart](https://github.com/burlykins/Disable-Windows-10-Telemetry/blob/master/Images/smallrestart.png)

Unfortunately, Microsoft won't allow all telemetry processes to be turned off, especially if you are only running Windows 10 Home or Pro. The Windows 10 Enterprise edition is allowed to turn off a few additional telemetry options that the Home and Pro users cannot, but you still aren't awarded full control of your computer's data. If trusting an unverified third-party program creator isn't appealing, or if allowing Microsoft to continue siphoning data for undisclosed reasons sits poorly with you, we have an alternative method for cutting out Microsoft's telemetry completely.

## **Cutting out Microsoft's telemetry completely**

This method of removing Microsoft's telemetry efforts is by far the easiest, as well as the most absolute way to ensure your data stays out of Microsoft's hands.

First, navigate to [Ubuntu.com](https://ubuntu.com/) then select the **"Downloads"** drop down icon located at the top of the page's header.

>![Clicking on Downloads will drop down more options](https://github.com/burlykins/Disable-Windows-10-Telemetry/blob/master/Images/ubuntudownload2.png)

Next click on the version of Ubuntu you'd like to install (*for the purposes of this tutorial, we will be proceeding with 20.04 LTS*). Save the .ISO image somewhere you can navigate to easily.

After the download has completed, you'll need to download a light and portable tool named Rufus over at [this link](https://rufus.ie/). Download the portable version, bypassing the need to install it. Rufus is a tool that will help us turn a flash drive into a bootable Ubuntu device using only the ISO image downloaded from ubuntu.com.

>![Click on the Portable version of Rufus](https://github.com/burlykins/Disable-Windows-10-Telemetry/blob/master/Images/rufus.PNG)

Next launch the portable Rufus program. After the program loads, insert a flash drive of at least 4GB (*make sure the device has no important information on it, all data will be formated and everything on the drive will be unrecoverable*). Next, Click on the top option field labeled **"Device"** and select the flash drive you intend to use.

>![Select the flash drive you intend to use](https://github.com/burlykins/Disable-Windows-10-Telemetry/blob/master/Images/rufusflashdrive.png)

The next step will be to select the Boot Selection. Click on the drop-down arrow under **"Boot selection"** and select **"FreeDos"**.

>![Select FreeDos Boot](https://github.com/burlykins/Disable-Windows-10-Telemetry/blob/master/Images/rufusboot1.png)

Next up is selecting the ISO image to write to the flash drive. Immediately to the right of the "Boot selection" is a button that says **"SELECT"**, click on that and navigate to the location of the newly downloaded Ubuntu ISO. Select the **ISO** and click **"Select"**.

>![Select the Ubuntu ISO](https://github.com/burlykins/Disable-Windows-10-Telemetry/blob/master/Images/rufusiso.png)

The final stage of making your Ubuntu Boot device is to click **"START"**. Some additional dialog boxes may appear before the process starts. If you get a dialog box with a header reading *"Downloads Required"* select **"Yes"**, next there could be a prompt stating that rufus detected a *"ISOHybrid image"*, select **"Write in ISO Image mode"** and hit **"OK"**.

>![Click Yes](https://github.com/burlykins/Disable-Windows-10-Telemetry/blob/master/Images/adddownloads1.png)
>![Click OK](https://github.com/burlykins/Disable-Windows-10-Telemetry/blob/master/Images/isoimagemode1.png)

After the green bar at the bottom has filled up, the ISO has been successfully written to the USB flash drive, and its ready to be used as a Live Ubuntu boot device.

## Booting into Ubuntu using Live USB flash drive ##

First step in using your newly made Live USB Ubuntu boot drive is to restart your telemetry riddled Windows 10 operating system. Make sure the Ubuntu flash drive is still in the computer when you restart your system. As soon as your computer starts the booting process, hit **"F12"** until you see your systems **Boot Menu**. From there, select the Ubuntu flash drive and hit **"Enter"**

>If F12 doesn't bring up the Boot Menu, restart your computer again and watch for a short message stating what button activates the boot menu; some motherboards have a different key that activates the boot menu

Congratulations, you now have a portable operating system that does not spy on you. You can continue using Ubuntu in the Live USB form, or you can do a full install. 

>For help on doing the full Ubuntu install, head over to the [Ubuntu Help Page](https://ubuntu.com/tutorials/tutorial-install-ubuntu-desktop#1-overview)
