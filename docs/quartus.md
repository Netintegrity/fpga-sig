# Quartus Installation

Created: 19 Oct 2021

## Overview

Just a quick note to document some 'gotchas' around installing
Intel's Quartus Prime Lite v20.1.1 software on Linux. A friend was
attempting to install it on Fedora 34 and was having troubles with
missing libraries. I managed to find these
[Debian Instructions](https://github.com/Jefferson-Lopes/quartus-installation).

According to the Quartus Prime install notes Red Hat 7 with KDE is 
Linux platform of choice. I can confirm that the software installs 
with CentOS 7 + KDE plasma desktop.

Once installed:

~~~bash
$ sudo yum install libXft*i686 libXext*i686 ncurses-libs*i686 bzip2*i686
~~~
