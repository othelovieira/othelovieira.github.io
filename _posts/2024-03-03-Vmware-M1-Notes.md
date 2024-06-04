### Installing Windows 11 on Apple Silicon with VMware Fusion - Indy Edition

![VMWare Image](/assets/images/prj_vmware_indy/VMware_Indy.jpg)

**Objective:**

Running Indiana Jones and the Last Crusade: The Graphic Adventure (Steam Edition) on Apple Silicon (M1).

**Prerequisites:**

You must have an Apple Silicon Mac running Fusion Pro or Player version 13.5 or later.

**Download and Install Windows 11:**

  - Open VMware Fusion.
  - Go to File > New.
  - In the dialog box named Select the Installation Method, choose Get Windows from Microsoft and click Continue.
  - The Download and Install Windows 11 window will appear.
  - Select your preferred Windows 11 edition and language.
  - Click Download Windows.
  - Fusion will download and create the Windows 11 ISO file for installation.
    
      Note the path to the ISO file will be Home>Virtual Machines>VMWIsoImages.
      You can use this ISO file to install Windows 11 in any number of virtual machines.
    
  -  Click Continue.

**Choose Firmware Type:**

  -  From the Choose Firmware Type dialog box, select a boot firmware (UEFI) and click Continue.
  -  Choose Encryption (Optional):
    
      If you want to enable encryption for the virtual machine (to satisfy vTPM requirements), select an encryption type, enter a password, and click Continue.
  
**Install Windows 11:**

-  Follow the installation prompts to complete the setup.

**Field Notes**

  -  You will still need a product key, a Windows 10 Pro / Home will work.

  -  If you have troube connecting to the internet change the VMWare Network settings to Bridged Network (WI-FI).

  -  After Windows is running install the VMware Tools.
  
  - Recommended reading - [The Unofficial Fusion for Apple Silicon Companion Guide](https://community.broadcom.com/home?s=The%20Unofficial%20Fusion%20for%20Apple%20Silicon%20Companion%20Guide&cs=null&l=1&expanded-categories=undefined)
