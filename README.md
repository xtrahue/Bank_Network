# Bank_Network
Design of a banking network using Cisco packet tracer.

<----About----->
The Bank has three floors.
i. The first floor has three departments(Reception, store and Waiting Room), in
ii. The second floor, there are three departments (Finance, HR and Staff Room),
iii. Third floor hosts the IT & Admin, Server Room.
Therefore, the following are part of the considerations during the design and implementation
1. There should be three routers connecting each floor (all placed in the server room to IT department).
2. All routers should be connected to each other using serial DCE cable.
3. The network between the routers should be 10.10.10.0/30, 10.10.10.4/30, 10.10.10.8/30.
4. Each floor is expected to have one switch (placed in the respective floor).
5. Each floor is expected to have WIFI networks connected to laptops and phones.
6. Each department is expected to have a printer.
7. Each department is expected to be in different I"LAN with the following details
1st Floor:
 Reception- SO, Network of 192.168.8.0/24
 Store- VIAN 70, Network of 192.168.7.0/24
 Waiting Room- VLAN 60, Network of 192.168.6.024
2nd Floor:
 Finance- VIAN 50, Network of 192.168.5.0/24
 HR- VLAN 40, Network of 192.168.4.024
 Staff Room- VLAN 30, Network of 192.168.3.0/24
3rd Floor:
 Admin & IT- VLAN 20, Network of 192.168.2.0/24
 Server Room- VLAN 10, Network of 192.168.1.0/24
9. Used OSPF as the routing protocol to advertise routes.
10. All devices in the network are expected to obtain IP address dynamically with their respective router configured as the DHCP server.
11. All the devices in the network are expected to communicate with each other.
12. Configure SSH in all the routers for remote login.
13. In IT department, add PC called Test-PC to port fa0/1 and use it to test remote login.



![image](https://github.com/xtrahue/Bank_Network/assets/108055347/1b9c1f07-6e78-4f0c-9d7a-ec62d3087af7)

Pinging From 3rd to 2nd Floor
![image](https://github.com/xtrahue/Bank_Network/assets/108055347/784f9e9d-7442-4af1-accb-824256ba215b)

Pinging from 3rd to 1st
![image](https://github.com/xtrahue/Bank_Network/assets/108055347/1e0eb9c9-21f8-43dc-821a-3a9e1f054acf)


