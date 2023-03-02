# DHCP configuration in a 3-Tier Campus LAN Architecture

![image](https://github.com/ascotlan/DHCP-configuration-in-a-3-Tier-Campus-LAN-Architecture/blob/main/topology.png)

## Abstract

This packet Tracer project is an extension of a previous project tiled as [“3-Tier Campus LAN Architecture with VLANs”](https://github.com/ascotlan/3-tier-campus-LAN-with-VLANs). In this project the goal was to allow automatic configuration of IP settings on the end hosts at the access layer instead of having to statically assign an IP address configuration on each end host added to the respective VLANs. The distribution switches in the Engineering building were successfully configured as DHCP relays for DHCP messages coming from the engineering and Computer Science VLANs. The distribution and access switches added in the administration building connected the DHCP standalone server to the rest of the network. DHCP messages from the server successfully reached the end hosts in the other building. Automatic IP configuration of all end hosts was achieved using DHCP.
