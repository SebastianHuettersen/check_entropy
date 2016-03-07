check_entropy
=============

What it does
------------

An agent based check for Nagios / Icinga / Icinga 2 for monitoring available entropy on a system.
The plugin uses the proc interface under '''/proc/sys/kernel/random/entropy_avail'''.

How to install
--------------

* Clone this repository somewhere you'll find it later
* Create a symlink to your plugin directory: '''ln -s check_entropy /usr/lib/nagios/plugins'''
* Create a symlink for the check command: '''ln -s checkCommand-entropy.conf /you/path'''
