kickstart-profiles
==================

Linux - CentOS6.6 RedHat - VirtualBox boot kickstart profiles

Kickstart Profile Installation
When the CentOS boot menu appears, highlight Install or upgrade an existing system, hit the Tab key to bring up the anaconda boot line, and append the following:

noverifyssl ks=https://raw.githubusercontent.com/kentucky-roberts/kickstart-profiles/master/centos-6-x86_64-vagrant-box.txt
Hit the Enter key and wait for the installation to finish.

At the end of the install, shutdown the virtual machine, and open Settings again for the virtual machine.

Go to the Storage tab, select Controller: IDE, and click the green square with red minus icon in the lower right hand corner of the Storage Tree section of the Storage tab.

Click OK to close the Settings menu.

Next, jump to the Create the Vagrant Box section.
