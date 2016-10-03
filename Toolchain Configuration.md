# AP Computer Science A Toolchain

* Java JDK - Java Development Kit
* Git - Version Control System (VCS)
* JetBrains IntelliJ IDEA - Integrated Development Environment (IDE) for Java

## Installation

### JDK

At home, you can download and install the JDK from [Oracle's Java download site][JDK]. At school it needs to be installed by tech services.

[JDK]: http://www.oracle.com/technetwork/java/javase/downloads/index.html

### Git

If you install git **before** installing IntelliJ, IntelliJ appears to be able to discover your git installation and configure itself to use it. If you installed IntelliJ first, then be sure to make note of where git is installed, you may need this information to set up git in IntelliJ.

1. Download [git][git]
1. Double-click on the downloaded file to run the installer.
1. There are a *lot* of dialog boxes, but I think you can safely select all of the defaults (but be sure to install **Git Bash**).

[git]: https://git-scm.com/downloads

### IntelliJ IDEA

1. Download [IntelliJ IDEA][IJ], the dowload button is in the middle of the page.
1. Double-click the downloaded file to install.

## Integration and Testing

Once you have the packages downloaded and installed it is time to configure them to work together and test them.

1. Launch IntelliJ
1. File > New > Project
1. Select your Project SDK - using the New button in the upper right hand corner (New > JDK). IntelliJ should have found your Java SDK, if not browse to it. After this it will be defaulted.
1. Continue through selecting nothing (just click on the Next buttons), until the last window (the one with a Finish button instead of Next), here you will name your project.
1. Click on VCS > Enable Version Control Integration and select Git from the drop down in the resulting dialog.
1. Click Yes and smile when prompted to add a file to git, I think this means that your git installation was detected.
1. Confirm that you have two active buttons in the upper right hand corner of the IntelliJ window, both with the text VCS, the one with the down-arrow updates your project from the git repository, the one with the green up-arrow commits your changes to the repository.
1. Click on the commit button (VCS with green up-arrow), you will get a dialog that asks you for a commit message and to confirm which files should be commited. Please select the "untracked files" and after adding your commit message, click on the Commit button.
1. You should get a dialog saying "Git User Name Is Not Defined." Enter your full name and the e-mail address associated with your GitHub account.


[IJ]: https://www.jetbrains.com/idea
