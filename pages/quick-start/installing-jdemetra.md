---
layout: left-menu
title: Installing JDemetra+
tagline: technical documentation for JDemetra+ using GitHub Pages
description: Basics
order: 1
---
JDemetra+ is a stand-alone application packed in a zip package. To run JDemetra+ the Java RE 8 or higher is needed. Java RE can be 
downloaded from [Java Web Site](www.java.com/en/download). 

The official release of JDemetra+ is accessible at 
[https://github.com/jdemetra/jdemetra-app/releases/tag/v2.2.0](https://github.com/jdemetra/jdemetra-app/releases/tag/v2.2.0). The site presents all available releases 
packed in zip packages. From the *Latest release* section either choose 
the Installer appropriate for your Operating System (Windows, Linux, 
macOS, Solaris) or take the portable zip-file. The installation process 
is straightforward and intuitive. For example, when the zip-file is 
chosen and downloaded, then under Windows OS the application can be found 
in the "bin"-folder of the installation/unpacked zip. To open an 
application, double click on nbdemetra.exe or nbdemetra64.exe depending 
on the system version (nbdemetra.exe for the 32-bit system version and 
nbdemetra64.exe for the 64-bit system version).

{: .text-center}
![Text](/assets/img/quick-start/RunningJDemetra.jpg)

Once downloaded to the PC it 
can be extracted to any folder on your system. The archive contains two 
versions of executable file (32-bit version and 64-bit version). The 
user should execute the version that matches the system version. The 
executable file is located in the appropriate *nbdemetra/bin* directory. 
If the launching of JDemetra+ fails, you can try the following 
operations: 
* Check if Java SE Runtime Environment (JRE) is properly 
installed by typing in the fol-lowing command in a terminal: java 
--version 
* Check the logs in your home directory: 
* %appdata%/.nbdemetra/dev/var/log/ for Windows; 
* ~/.nbdemetra/dev/var/log/ for Linux and Solaris; 
* ~/Library/Application Support/.nbdemetra/dev/var/log/ for Mac OS X. 
In order to remove a previously installed JDemetra+ version, the user 
should delete an appropriate JDemetra+ folder. 

