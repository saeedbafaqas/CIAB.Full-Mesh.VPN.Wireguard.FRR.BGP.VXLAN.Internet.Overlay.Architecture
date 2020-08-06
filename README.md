# CIAB Full Mesh VPN Internet Overlay

The ***Cloud In A Box (CIAB)*** project introduces what we describe as the 
***CIAB Full Mesh VPN Internet Overlay Architecture***.

### Definitions  

***Full Mesh** means any node can reach any other node directly without going through some central node.*  
***Virtual Private Network (VPN)** means your entire Internet Overlay is fully encrypted end-to-end.*  
***Overlay** Network overlays are a method of using software virtualization to create additional layers 
of network abstraction (or software-based network overlays) that can be run on top of the physical network, 
often providing new applications or enhanced security benefits.*

## Goals of the CIAB Mesh VPN Internetworking Overlay Project

The ideal solution to satisfy the goals of this project will include the following
***Key Performance Indicator (KPI)*** success factors:
  
> **1. Security and Secure communications  
> 2. Open Source  
> 3. Supports use of LXD Containers & VMs and LXD related technologies  
> 4. Easy/simple installation, configuration and expansion  
> 5. Multi-node (re Multi LXD Host/Server) capable, intranet or Internet  
> 6. Multi-Cloud and Hybrid Cloud capable**  

Everything is implemented using Open Source tools and applications:   
 
- **Linux (I use Ubuntu)**
- **[Wireguard VPN](https://www.wireguard.com/)**
- **[VxWireguard-Generator](https://github.com/m13253/VxWireguard-Generator)**
- **[Free Range Routing - FRR](https://frrouting.org/)**
- **[FRR's BGP and BGP-VRF protocols](http://docs.frrouting.org/en/latest/bgp.html)**  
- **[Virtual eXtended LAN - VXLAN](https://user-images.githubusercontent.com/1682855/89578990-02194980-d801-11ea-8f39-62c74b625732.png)**   
- **[LXD VMs and Containers](https://linuxcontainers.org/lxd/docs/master/)**  
  
For complete step-by-step installation/configuration instructions see:

**[The CIAB Mesh VPN Internet Overlay Installation Guide](https://github.com/bmullan/CIAB-Mesh-VPN-Wireguard-FRR-BGP-VXLAN-Internet-Overlay/blob/master/CIAB%20Mesh%20VPN%20Internet%20Overlay%20Installation%20Guide%20%20-%20single-tenant.pdf)**

**[CIAB's Mesh VPN Utility Scripts - used to start/stop/restart etc Wiregard, FRR, BGP](https://github.com/bmullan/CIAB-Mesh-VPN-Wireguard-FRR-BGP-VXLAN-Internet-Overlay/blob/master/ciabvpn-utility-scripts.tar.gz)**

*Utilizing the CIAB Mesh VPN Internet Overlay you can quickly connect LXD VM's and LXD Containers
running in your Single/Multi-Tenant, Multi-Node/Server, Multi-Cloud or Hybrid/Cloud Datacenters.*

All **data traffic is highly encrypted end-to-end** by Wireguard's VPN.

VxLAN supports Layer2/3 with Layer 3 preventing flooding your Overlay Network with **Broadcast, Unknown and Multicast (BUM) traffic**.

