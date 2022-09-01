+++
title = "RDS Analyst"
author = ["Mark S. Handcock"]
draft = false
+++

## Introduction

<u>RDS Analyst</u> ('RDS-A') is a software package for the analysis of
Respondent-driven sampling (RDS) data that implements recent advances in
statistical methods.

<u>RDS Analyst</u> has an easy-to-use graphical user interface to the powerful and sophisticated capabilities of the computer package
[R](https://r-project.org).  <u>RDS Analyst</u> provides a comprehensive framework for working with RDS data, including tools for sample and
population estimations, testing, confidence intervals and sensitivity analysis.

Example capabilities are an easy format for entering data, the visualization of
recruitment chains, regression modeling, and missing data.

The interface of <u>RDS Analyst</u> is similar to [SPSS](https://www.spss.com/). <u>RDS Analyst</u> is
also a free, easy to use, alternative to proprietary data analysis software
such as [SPSS](https://www.spss.com/), [STATA](https://www.stata.com/),
[SAS](https://www.sas.com/)/[JMP](https://www.jmp.com/), and
[Minitab](https://www.minitab.com/). It has a menu system to do common data
manipulation and analysis tasks, and an Excel-like spreadsheet in which to view
and edit data.

<u>RDS Analyst</u> is meant for users who want to use state-of-the-art techniques for
estimation and quantification of uncertainty from data collected via RDS. It
represents advanced, comprehensive and open-source software to visualize, model
and conduct sensitivity analyzes for RDS data.

<u>RDS Analyst</u> is an intuitive, cross-platform graphical data analysis system for
the analysis of RDS data. It uses menus and dialogs to guide the user
efficiently through the data manipulation and analysis process, and has an
Excel-like spreadsheet for easy data frame visualization and editing. It is
also the front-end to the very powerful capabilities accessible via the
[R](https://r-project.org) command-line interface and also the extensive
capabilities of the [R](https://r-project.org) statistical language.

## Basic facts
* <u>RDS Analyst</u> is written for the [R](https://r-project.org) statistical environment.
* The current development form is for Windows and Macintosh. A LINUX version will be available in installers when it is released publicly.

## Installation on an Windows PC

The installer is [here](https://drive.google.com/file/d/1Zu6YOe7J7IN5s-o7IVRPJAMpZFC-0C3G/view?usp=sharing).

<!--https://neolab.stat.ucla.edu/cranstats/RdsAnalystSetup.0.42.exe -->
<!--https://hpmrg.org/software/RDSAnalystSetup.0.7.exe-->

Download the installer and double-click on it to install the software. 

This can install all programs and utilities needed. If you already have some elements installed you can deselect (or cancel) during the
installs. It is recommended that you install this all the first time. This installer is almost 400Mb in size and will take time to download.

A reboot is not required. You do not need to uninstall any components to update (This includes R and Java). However the <u>RDS Analyst</u>
application or the R application must not be running when you update.

<!--- After you install, you <b>should</b> use the updater to keep your installation to the latest version of the packages:-->
<!---* Download the <u>RDS Analyst</u> Updater: https://hpmrg.org/software/RDSAnalystUpdater.0.62.exe -->
<!--- This just installs minor updates for the core packages (that is, anything that has changed since the full install was made). It will
typically be a few Mb in size.-->
<!---After you install, you <b>should</b> use the updater to keep your installation to the latest version of the packages:-->
<!-- -->
<!--- Download the <u>RDS Analyst</u> Updater: https://hpmrg.org/software/RDSAnalystUpdater.0.62.exe -->
<!--- -->
<!--- This just installs minor updates for the core packages (that is, anything that has changed since the full install was made). It will
typically be a few Mb in size. -->
<!--- You need the Java Runtime Environment to use  <u>RDS Analyst</u>. You can check to see if you have java installed at
https://javatester.org/version.html -->
<!--- If you get the message <i>A JRE has been found. Do you want to install another one anyway?</i>, it means that Java is already installed.
In this case, click <i>No</i> so as to not reinstall it.-->
This is a new portable version that does not need  the Java Runtime Environment to use.
<!--- You need the Java Runtime Environment to use  <u>RDS Analyst</u>. You can check to see if you have the right java installed through the
Windows Start menu:-->
<!--- # Launch the <b>Windows Start</b> menu-->
<!--- # Click on <b>All Apps</b>-->
<!--- # Find the <b>Java</b> program listing-->
<!--- # Click <b>About Java</b> to see the Java version -->
<!--- If you get a result like [[Media:RDSA_MAC_Java.png|this]], it means that Java is correctly installed.If there is no <b>Java</b> listing
or an earlier version number you do not have Java correctly installed. In this case, in the installer click <i>Yes</i> so as to install it -->

<!--  If you do not have Administrator privileges and the Java Runtime Environment is not installed then you will not be able to run  <u>RDS
Analyst</u>. -->


*Note for experienced users:*
This creates a private version of R for <u>RDS Analyst</u> to use and ensures <u>RDS Analyst</u> has the right version of R available for its
use.  If you already have R installed separately, the two versions will peacefully coexist and you can use the other version of R just as you
were originally.

<b>Finally, be sure to sign up for the</b> [RDS Analyst Users Group](#rdsa-help)

## Installation on an Apple Macintosh

There is a version for Apple Macintosh computers. <!-- They must have Intel CPUs (i.e., be purchased post-2006). -->

The installer is [here](https://drive.google.com/file/d/1-2rf7TMOvY8_uZ4NzWPbhUEipKSVqYE7/view?usp=sharing)

<!--https://hpmrg.org/software/RDSAnalystInstaller.0.71.dmg-->

Download the installer and double-click on it to install the software. 

This can install all programs and utilities needed. If you already have some elements installed you can deselect (or cancel) during the
installs. It is recommended that you install this all the first time. This installer is almost 400Mb in size and will take time to download.

A reboot is not required. You do not need to uninstall any components to update (This includes R and Java). However the <u>RDS Analyst</u>
application or the R application must not be running when you update.

The <u>RDS Analyst</u> application and R will be in your Applications folder. To run <u>RDS Analyst</u>, double-click on it in the Applications
folder.

This is a new portable version that does not need the Java Runtime Environment to use.

*Note on Xcode and gfortran:*
Some Macs need the application Xcode and a version of Fortran to be installed. Xcode is software written by Apple to help people develop
software on the Mac, including compiling some R packages from source code. In some cases, <u>RDS Analyst</u> will not run unless it is
installed.

Here are the steps:

* Install the Xcode application from the Mac App Store
* Open the installed Xcode app, agree to the license, and let it install some "components"
* Open a terminal window by opening the Terminal application (Applications > Utilities > Terminal).
Type <i>xcode-select --install</i> and follow the dialogs that open. This installs some tools for making R packages from source.
* Install gfortran by downloading the installer at:  https://cran.r-project.org/bin/macosx/tools/gfortran-4.2.3.pkg
The file will be an Apple style installer (.pkg) which you will need to open to install gfortran on your computer.
It should install by default in /usr/local/bin/gfortran.

*Note for experienced users:*
This creates a private version of R for <u>RDS Analyst</u> to use and ensures <u>RDS Analyst</u> has the right version of R available for its
use.  If you already have R installed separately, the two versions will peacefully coexist and you can use the other version of R just as you
were originally.

<!-- After you install, you <b>should</b> use the updater to keep your installation to the latest version of the packages: -->
<!-- -->
<!-- * Download the <u>RDS Analyst</u> Updater: https://hpmrg.org/software/RDSAnalystUpdater.0.51.dmg -->
<!--** It should mount as a disk-image. Double-click on the installer in it (i.e., "RDSAnalystUpdater") to install the software.-->
<!---->
<!--This just installs the core packages (that is, anything that has changed since the full install was made). It will typically be 15 Mb in
size.-->
<!---->
<!--Note: To use <u>RDS Analyst</u>, you need Java installed on your Mac. If you are using Mac OS X 10.6 and below, Apple's Java comes
pre-installed. If you are using -->
<!-- Mac OS X 10.7 (Lion) or Mac OS X 10.8 (Mountain Lion) and above then Java is not pre-installed.-->
<!-- To get the latest Java 7 from Oracle, you will need Mac OS X 10.7.3 and above. -->
<!-- If you have Java 7, you will see a Java icon under System Preferences.--> 
<!-- To install Java version 6, open the "Java Preferences.app" located in the Applications > Utilities folder on your Mac. It will ask if you
want to install Java if it is not already there. Accept its invitation.-->

<!-- Here is an installation video (coming). -->

<b>Finally, be sure to sign up for the</b> [RDS Analyst Users Group](#rdsa-help).

## Getting started - The Manual

For the manual, go to the [RDS Analyst Manual](https://www.deducer.org/pmwiki/pmwiki.php?n=Main.RDSAnalyst)

## RDS Analyst citation information

To cite <u>RDS Analyst</u>, go to [citation](citation).

## RDS Analyst Discussion and Help Forum
<a name="rdsa-help"></a>

The best way to contact us with questions, comments or suggestions is through the RDS Analyst users group.

To post and receive messages from this forum, you need to join. To subscribe, go to
[rdsanalyst_help](https://groups.google.com/forum/?hl=en#!forum/rdsanalyst_help).

You can use the forum to:

* get help from the Hard-to-Reach Population Methods Research Group and other users
* post questions, comments and ideas to other users
* be informed about RDS Analyst updates
* learn about bugs (and bug fixes) 

* If you find bugs, please report them and use "Bug:" in the subject line. 
* For software feature requests, use "Feature Request:" in the subject line.

Once you have joined the list, you can post your questions and comments to
[rdsanalyst_help@googlegroups.com](mailto:rdsanalyst_help@googlegroups.com).

A full list of all messages posted to this list is available [here](https://groups.google.com/group/rdsanalyst_help).

Enjoy!
