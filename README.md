![Bank Network](https://user-images.githubusercontent.com/72334419/235219042-f107bffb-61f6-4264-a976-d0abd8c58f84.png)

# Banking Network in Packet Tracer

The Government has secured a four-story building for operating Bank within the Valsad City, India.

<b>4th floor</b>
- Admin - Vlan 100
- ICT - Vlan 110
- Server Room  - Vlan 120 - DHCP, HTTP, E-mail

<b>3rd floor</b>
- Logistcs & Store - Vlan 70
- Customer Care - Vlan 80
- Guest Area - Vlan 90

<b>2nd floor</b>
- Marketing - Vlan 40
- Accounting - Vlan 50
- Finance - Vlan 60

<b>1st floor</b>
- Management - Vlan 10 

- Research - Vlan 20
- HR - Vlan 30

<n><b># Tasks</b></n>
- Use OSPF as the routing protocol to advertise routes.
- Each department is required to have a wireless network for the users.
- Each department except the server room will be anticipated to have around 60 users both wired and wireless users.
- Host devices in the network are required to obtain IPv4 addresses automatically.
- Devices in all the departments are required to communicate with each other.
- Create HTTP, and E-mail servers.
- All devices in the network are expected to obtain an IP address dynamically from the dedicated DHCP servers located at the server room.
- Configure SSH in all the routers for remote login.
- Configure the basic configuration of the devices: Hostnames, Line Console and Enable passwords, Banner messages Disable domain IP lookup, encrypt all configured passwords.
- Each department should be in a different VLAN and subnetwork; VLANs you will use in your case, e.g. 10, 20, 30… etc..
- Planning of IP Addresses: You have been given 192.168.10.0 as the base address for this network. Do subnetting based on the number of hosts in every department as provided above. Identify subnet mask, useable IP address range, and broadcast address for each subnet.
- End Device Configurations: Configure all the end devices in the network with the appropriate IP address based on the calculations above.
- Configure port-security: Use sticky command to obtain MAC Address and Violation mode of the shutdown.
- Test and Verifying Network Communication.

<n><b>Technologies Implemented</n></b>
- Creating a network topology using Cisco Packet Tracer.
- Hierarchical Network Design.
- Connecting Networking devices with Correct cabling.
- Configuring Basic device settings.
- Creating VLANs and assigning ports VLAN numbers.
- Subnetting and IP Addressing.
- Configuring Inter-VLAN Routing on the Multilayer switches (Switch Virtual Interface).
- Configuring Dedicated DHCP Server device to provide dynamic IP allocation.
- Configuring SSH for secure Remote access.
- Configuring OSPF as the routing protocol.
- Configuring switchport security or Port-Security on the switches.
- Configuring WLAN or wireless network (Cisco Access Point).
- Host Device Configurations.
- Test and Verifying Network Communication.

<n><b>#Configuration Files</b></n>
[Banking_Network_Floor1_Config.odt](https://github.com/Krupal08/Bank-Network/files/11404034/Banking_Network_Floor1_Config.odt)
[Banking_Network_Floor2_Config.odt](https://github.com/Krupal08/Bank-Network/files/11404035/Banking_Network_Floor2_Config.odt)
[Banking_Network_Floor3_Config.odt](https://github.com/Krupal08/Bank-Network/files/11404036/Banking_Network_Floor3_Config.odt)
[Banking_Network_Floor4_Config.odt](https://github.com/Krupal08/Bank-Network/files/11404037/Banking_Network_Floor4_Config.odt)

