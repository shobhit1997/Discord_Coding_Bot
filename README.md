Steps:

    Installation of required tools:

    git
    any IDE of your choice (for ex. sublime text and atom)
    Java

Installing git:

Ubuntu:
sudo apt-get install git
Windows: Use this link:
https://git-scm.com/download/win
Mac: https://git-scm.com/download/mac
Contributing to this repository:

    Star this repository
    Fork this repository
    Open users.md and enter details in the following format
    Name: "Your name here"
    Place: "Enter place here"
    Bio: "Enter about yourself here"
    Github: [Github username](github profile url)
    Facebook (optional): [Your name](facebook profile link)
        make sure to give 2 whitespaces after each line.
    Commit changes with a meaningful commit message like "Added "Your Name to users.md".
    Create a pull request.
    Sit back and relax while your pull request is reviewed and merged.

Installing Java:

Windows

This guide will guide you through the process of downloading and installing Java on Microsoft Windows.

    Visit the Java website and download the installer

    To install Java, you first need to download the installer program from Oracle.

    Visit the "Download Java" page: https://java.com/download

    Click the "Free Java Download" button.

    You are then prompted to read and agree with the end user license agreement.

    Depending on which web browser you are using to download Java and depending on its configuration, you may be prompted to either Download, Save or Run the installer file.

    If you are prompted to run the Java installer file from Oracle, it is ok to just click the Run button. You also may prefer to save it to your disk and then manually find and run the installer yourself.
    Run the installer

    Depending on your Windows Security Settings, you may be prompted to allow the Java Installer to modify files on your computer. This is an important safeguard to make sure you really want to let software you've downloaded from the internet make changes to your computer. Please make sure this is the correct installer file and then when you're satisfied that it is, click the "Yes" button.

    Install Java

    You are now shown the Java installer program.

    You can optionally change the Java install destination folder (using the checkbox in the bottom left), however this is an advanced option and should only be used by users who have a specific need to configure Java. It is fine to ignore this option.

    When you have read and are ready to accept the license agreement, click the "Install" button.

    Java will now download and install itself.

    Congratulations, you have now installed Java.

    Click the 'Close' button and Java will reopen your web browser to verify itself
    Verify Java

    The Java installer will open your default web browser and prompt you to verify your Java installation.
   Ubuntu

   Installing default JRE/JDK

This is the recommended and easiest option. This will install OpenJDK 6 on Ubuntu 12.04 and earlier and on 12.10+ it will install OpenJDK 7.

Installing Java with apt-get is easy. First, update the package index:

sudo apt-get update

Then, check if Java is not already installed:

java -version

If it returns "The program java can be found in the following packages", Java hasn't been installed yet, so execute the following command:

sudo apt-get install default-jre

This will install the Java Runtime Environment (JRE). If you instead need the Java Development Kit (JDK), which is usually needed to compile Java applications (for example Apache Ant, Apache Maven, Eclipse and IntelliJ IDEA execute the following command:

sudo apt-get install default-jdk

That is everything that is needed to install Java. 

Mac Os

Install Java on Mac

    Download the jre-8u65-macosx-x64.pkg file.
    Review and agree to the terms of the license agreement before downloading the file.
    Double-click the .pkg file to launch it
    Double-click on the package icon to launch install Wizard


    The Install Wizard displays the Welcome to Java installation screen. Click Next


    Oracle has partnered with companies that offer various products. The installer may present you with the option to install these programs when you install Java. After ensuring the desired programs are selected, click the Next button to continue the installation.

    Example of Yahoo offer dialog
    Known Issues
    [macosx] Sponsor offer screen accessibility (a11y) issues

    Users who operate the keyboard to access user interfaces in the Java installer will be unable to access hyperlinks and checkboxes in software add-on offer screens. As a workaround to setting preferences related to add-on software in the user interface, users can disable such offers either by disabling them in the Java control panel, or by passing SPONSORS=0 via the command line. For more information, refer to Install Java without sponsor offers FAQ.
    After the installation has completed, a confirmation screen appears. Click Close to finish the installation process.


