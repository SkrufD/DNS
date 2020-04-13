# DNS
Local network DNS with blocking using Pi-hole, Unbound and NSD.

This repository has the main configuration files I used to create a local network DNS system using Pi-hole for ad-blocking with Unbound as the Internet reaching DNS and NSD for the local DNS service. Yes, a hosts file will work for local resolution but NSD requires a bit more brain power and as one gets older it becomes even more important it is to keep exercising that portion of ourselves.

Currently using a Raspberry Pi 3 Model B+ running Raspbian Buster Lite. Actually run two of them but not in a Master/Slave configuration. Things do not change much and if one gets cocky or runs off there's redundency... Now if they both pack up and leave, well I guess that's why you clone the SD card!

I did a lot of looking and reading on sites that had configuration examples and step-by-step tutorials on how to set this up from scratch... I'm not going to attempt to do that, but I thought posting my configs might benefit someone else... so...

I started out by installing Raspbian Buster Lite... https://www.raspberrypi.org/downloads/raspbian/

Then I used the "Pi-hole as All-Around DNS Solution" located here... https://docs.pi-hole.net/guides/unbound/

