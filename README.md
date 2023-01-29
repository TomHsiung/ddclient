# ddclient
A small dynamic DNS service

# Contents
1) The `ddclient.web.conf` file is the main configuration file for ddclient service, and works in a manner that the IP address to update is fetched as web public IP address.
2) The `ddclient.eth.conf` file is the main configuration file for ddclient service, and works in a manner that the IP address to update is fetched as the ethernet card's IP address.
3) With the version 3.9.1-7, the file of ddclient which locates in the path of /etc/default, determines the behavior of ddclient daemon.

# Notice
Make sure to reload or restart the ddclient service after modifying the `ddclient.conf` file.
