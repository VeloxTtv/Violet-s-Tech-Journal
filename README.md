# Violet-s-Tech-Journal
A tech journal created for Network Fundamentals (NET-150).

Lab 1: Installed Kali as a VM to Oracle Virtualbox and screenshotted the ip addr output.

Lab 2-0: Installed Windows as a VM to Oracle Virtualbox and screenshotted the ipconfig /all output.

Lab 2-1: Meant to register for a net academy account, and get started with Packet Tracer. Unable to complete at this time.

Lab 2-2: Observed Lan activity in Wireshark, recording source and destination Mac addresses as well as the wifi's default gateway. 

Lab 3-1: Observed ARP requests and replies over LAN using Wireshark. The command we used to dumb the ARP cache in linux was sudo ip neigh flush all.

Lab 3-2: Observed ARP requests and replies over LAN using Wireshark. Learned that the destination MAC address isn't that of what you're pinging but is likely the MAC address of the router.

Lab 4-2: Created 3 routers each with one switch and two IP addresses. Experimented with learning network and broadcast IP's, first and last usable host IP's, and /27 networks.

Lab 5-2: Created a network in packet tracer independantly. When setting computers IP's statically, the default gateway should be the same as the roouters configured IP for the port. Make sure to add info to RIP, if network is 192.168.1.1 add 192.168.1.0 to RIP.

Lab 6-1: Practiced making networks in Packet Tracer. Got a refresher on CIDR notation. (2^(32-n) where n is the prefix in CIDR notation)

Lab 9-1: Configured static ip routes for routers in packettracer using the command ip route (ip) (subnet mask) (interface), for example ip route 192.168.20.0 255.255.255.0 10.10.20.1. Also discussed why this method of configuring static routes for each router is unideal on a larger scale.

Lab 9-2: Did more static route configuring, this time using the window in config. It's the same premise with the same info, just less time consuming. Utilized more CIDR notation math.

Lab 10-1: Utilized RIP V2 to create IP routes as an alternative to static routing, remember RIP caps out at 15 hops, anything 16 or greater is unreachable. Basic commands to remember for CLI in order to use RIP V2 are as follows: 1. router rip 2. version 2 3. network *network address*
