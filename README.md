VLAN & DHCP – Router-on-a-Stick Lab

In diesem kleinen Netzwerkprojekt habe ich einen Cisco-Router, einen Switch und drei PCs konfiguriert.
Ziel war es, mehrere VLANs einzurichten und jedem über DHCP automatisch IP-Adressen zuzuweisen.

---Überblick

Router: Router-on-a-Stick mit Subinterfaces (VLAN 10, 20, 30)

Switch: Access-Ports für die PCs, Trunk-Port zum Router

DHCP: Drei Pools für HR, IT und Sales

VLAN	Abteilung	Netzwerk
10	HR	192.168.10.0/24
20	IT	192.168.20.0/24
30	Sales	192.168.30.0/24


--------------------------------------------------------------------------------------------------------------------------------


In this small network lab, I configured a Cisco router, a switch, and three PCs.
The goal was to set up multiple VLANs and assign IP addresses via DHCP automatically.

Router: Router-on-a-Stick with subinterfaces (VLAN 10, 20, 30)

Switch: Access ports for PCs, trunk port to the router

DHCP: Three pools for HR, IT, and Sales

VLAN	Department	Network
10	HR	192.168.10.0/24
20	IT	192.168.20.0/24
30	Sales	192.168.30.0/24