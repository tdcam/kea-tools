# kea-tools
Playbooks to install and configure kea DHCP server

The expectation is that you'll use the install_kea.yml to install the package 
and enable it, then append_reservation.yml to update the Kea dhcp server config.

You'll set up survey questions including:

hostname
mac_addr
ip_addr

Once you set those up, you only need to enter them in the survey. The config file
will be updated and the kea-dhcp4 service will be restarted.
