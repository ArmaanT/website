---
title: "Homelab"
summary: "An intranet to learn and make my life easier"
tags: ["sysadmin", "devops"]
date: 2019-08-22T14:42:41-04:00
---
My connected home network (or [Homelab](https://www.reddit.com/r/homelab/wiki/introduction)) consists of 2 physical servers, a virtual-machine host ([Proxmox](https://www.proxmox.com/en/)) and a File server ([FreeNAS](https://www.freenas.org/)). Proxmox runs over 25 virtual machines and containers. The Homelab provides various services such as a software firewall, a remote SSH access server, a reverse proxy with [Lets Encrypt](https://letsencrypt.org/) TLS certificates, a VPN server with certificate authentication, a wiki for internal documentation, a mail server to send external mail, and a home automation system. Some of the software using in my homelab is: FreeNAS, Gitlab, Grafana, InfluxDB, Jekyll, Mediawiki, MySQL, Nginx, OpenHAB, pfSense, Postfix, and Telegraf. 