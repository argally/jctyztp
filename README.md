# OVERVIEW

  "Junos Config To Your ZTP" server  
  
  This example illustrates a hybrid technique for "zero touch provisioning".  It combines Junos features [autoinstallation](http://www.juniper.net/techpubs/en_US/junos12.3/topics/concept/ex-series-configuration-files-autoinstallation.html) or [ZTP](http://www.juniper.net/techpubs/en_US/junos12.3/topics/task/configuration/software-image-and-configuration-automatic-provisioning-confguring.html) with your backend webserver.  The goal of this process is to simplify the DHCP server configuration, and allow for per-device Junos OS and configuration installation.
  
  Junos products that support autoinstallation or ZTP utilize a DHCP and TFTP process to obtain an IP address and initial configuration file (aka bootfile).  Typically the DHCP server is used to map MAC addresses (or something device specific) to a specific configuration file.  The ZTP process goes one step further to use DHCP options to identify a Junos software image.  
  
  
  
  
  
  
# LICENSE
BSD-2, see [LICENSE](LICENSE.md) file
