---
title: Virtual Private network
date: 2026-11-04
draft: false
tags: ["XSS", "LPE"]
---

## Site-To-Site Vpn

When both the client and server are network devices. Used to join company networks together.

## Remote Access VPN

Client creates a virtual interface to behave as if its on a client’s network. 

If the VPN routes all the devices network traffic through the company’s VPN gateway, then out to internet or internal resources, it is a Full-Tunnel VPN.

If VPN only creates routes for specific networks, it is called a Split-Tunnel VPN, meaning Internet connection is not going out the VPN. For a company, Split-Tunnel is not ideal because if the machine is infected with malware, network-based detection methods will most likely not work as that traffic goes out the Internet.
