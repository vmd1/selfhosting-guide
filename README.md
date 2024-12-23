# Self-hosting with docker, a guide to all the services I use

## Services Run:
This is a WiP, I'll start by listing out all the services, but not all of them will have guides yet in this repository. Some of these setups may not be best practise, so please do let me know if you think there are any good changes that could be made, by making an issue.

A brief explanation of my own personal setup, I am running 4 nodes, two of which are free-tier Oracle Cloud VMs with the sole purpose of just running some small backup services, e.g. Nginx Proxy, Uptime-Kuma, and DNS. The other two are a Raspberry Pi 5, and a Raspberry Pi 3. 

Server names:
- Ultimate - Raspberry Pi 5
- Ultimate-rpi3 - Raspberry Pi 3
- UK-South-1 - Oracle VM
- UK-South-2 - Oracle VM

List of Services Run:
- Home Assistant - Ultimate
- 2FAuth - Ultimate
- Beszel - Ultimate
- Beszel Agents - All servers
- Bookstack - Ultimate
- DNS - Ultimate, Ultimate-rpi3, UK-South-1
- Dockerproxy - Ultimate
- Glances - All servers
- Homepage - Ultimate, Ultimate-rpi3
- Hosting - Ultimate, UK-South-2
- Immich - Ultimate
- Ipinfo.tw - Ultimate
- Jellyfin - Ultimate
- Lldap - Ultimate
- Dockge - All servers
- Nginx Proxy Manager - Ultimate, UK-South-2
- Unifi Controller - Ultimate
- KMS Server - UK-South-1
- Uptime Kuma - Ultimate, UK-South-2
- VPN (Wireguard) - Ultimate, Ultimate-rpi3
- VPN (Tailscale) - All servers
- Watchtower - Ultimate, Ultimate-rpi3
- Kasm Workspaces - Ultimate
- Crafty Controller - Ultimate
- Dozzle - All servers
- Element Web - Ultimate, UK-South-1
- Kiwix - Ultimate
- Matter Server + Bridge - Ultimate
- MQTT - Ultimate
- Ring-MQTT - Ultimate
- Shlink - Ultimate
