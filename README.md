
<h1>MPLS L2/3 Switches</h1>

<!-- ### [Kaltura Capture Recording](https://mediaspace.minnstate.edu/media/Kaltura+Capture+recording+-+April+26th+2025%2C+11%3A11%3A10+pm/1_sp0j5ef9) -->

<h2>Description</h2>
This project simulates MPLS-like Layer 2/3 switching behaviour using Cisco multilayer switches in Cisco Packet Tracer. The setup involves two VLANs configured on separate switches, each representing a distinct broadcast domain:

Project Highlights:
1. Multilayer switching is configured on both ends to route between VLANs at Layer 3.
2. A trunk link is established between the switches to carry tagged VLAN traffic across the backbone.
3. Demonstrates VLAN isolation and inter-VLAN communication through SVI (Switched Virtual Interface) configuration.
4. Reflects a simplified MPLS-like architecture, where data forwarding is handled at Layer 2 while routing decisions are made at Layer 3.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Cisco IOS CLI commands</b> 

<h2>Environments Used </h2>

- <b>Cisco Packet Tracer</b> (8.2)

<h2>Program walk-through:</h2>

<p align="center">
Network Design: <br/>
<img src="https://i.imgur.com/5ML61L8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enabling routing (IP routing) and Configuration of Switchport modes: access and trunk ports(Multilayer Switch2 (L2/3 Switch)): <br/>
<img src="https://i.imgur.com/zIEraBI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuration of Vlan 10 & Vlan 20 (Multilayer Switch2 (L2/3 Switch)):  <br/>
<img src="https://i.imgur.com/JVM4t8h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configuration of Switchport modes: access and trunk ports(Multilayer Switch3 (L2 Switch)): <br/>
<img src="https://i.imgur.com/m6yQGVP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
Verifying the Configuration is successful (PC0 ping):  <br/>
<img src="https://i.imgur.com/TsfX7BK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Verifying the Configuration is successful (PC1 ping):  <br/>
<img src="https://i.imgur.com/HEcPtMc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

