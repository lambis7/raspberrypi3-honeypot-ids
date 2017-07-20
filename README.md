# raspberrypi3-honeypot-ids

This is a guide on how to install both Kippo SSH Honeypot and Snort IDS with Barnyard2, Pulledpork and Snorby on Raspberry Pi 3 running Raspbian OS.

This work is based on the work of Maltego Magician (https://itgeekchronicles.co.uk/2013/05/14/honeypot-kippo-pi/) and Noah Dietrich and his guide "Snort 2.9.8.x on Ubuntu 12, 14, and 15, with Barnyard2, PulledPork, and Snorby" with the necessary changes, libraries additions and so on in order to run those two applications on a Raspberry Pi 3 with RaspbianOS.

NOTE: 
1) Kippo-Graph cannot be installed on Raspberry Pi 3 with Snorby already installed on it, due to some limitations of its installation and the Apache Web Server settings. You can export the kippo database, and insert it on a VM with kippo-graph installed to view the results.
Instructions on how to install kippo-graph is included in this guide.
2) Lines with hash symbol (#) are comments.
