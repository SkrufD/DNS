# DNS
Local network DNS with blocking using Pi-hole, Unbound and NSD.

This repository has the main configuration files I used to create a local network DNS system using Pi-hole for ad-blocking with Unbound as the Internet reaching DNS and NSD for the local DNS service.

Currently using a Raspberry Pi 3 Model B+ running Raspbian Buster Lite. Actually run two of them but not in a Master/Slave configuration. Things do not change much and if one gets cocky or runs off there's redundency... 

I did a lot of looking and reading on sites that had configuration examples and step-by-step tutorials on how to set this up from scratch... I'm not going to attempt to do that, but I thought posting my configs might benefit someone else... so...

I started out by installing Raspbian Buster Lite... https://www.raspberrypi.org/downloads/raspbian/

Then I used the "Pi-hole as All-Around DNS Solution" located here... https://docs.pi-hole.net/guides/unbound/

