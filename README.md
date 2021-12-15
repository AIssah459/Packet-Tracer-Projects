# Packet-Tracer-Projects

## Intro

This is a GitHub repository containing all my Packet Tracer Project files, which can be readily downloaded and run in a Cisco Packet Tracer Client. I'll also include the running configurations for each project. This repo is simply a "portfolio" to showcase what I've been learning with Cisco IOS. I made this repo because I don't have the means to buy physical machines for a home lab, so I make packet tracer labs to practice, and when I've made something that I think showcase my skills well, I'll add it on here.

## Projects

Here's some explanations for each project:

### EIGRP-Lab
This lab is simply practicing creating routes between networks with eigrp, as well as dynamic addressing as provided by DHCP. I set up two LANs with each its own router-on-a-stick topology (as well as inter-VLAN routing). Both LANs are connected together with an intermediate router, which forms the backbone of the communcation.

### VPN-Lab
This lab is practicing IPSec and site-to-site VPN. It is two LAN networks with outward-facing routers, which are in turn connected by an "ISP" router. First, I set up an acl rule. Then I set up ISAKMP profile, key (phase 1), and ISAKMP transform-set (phase 2). I also set up crypto maps on each end, and applied the rules on the appropriate interfaces, and set up a default static route to the "ISP" router. In this lab, I didn't set any routing protocol (RIP, OSPF, EIGRP), just IPSec tunnel.
