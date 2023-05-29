# NETWORKING-PACKAGE



CN PACKAGE ABSTRACT
Hotel Management network design

Team members:

Vishal.V (21PT36)
S.HITESH (21PT21)

We are designing and implementing Modern Hotel network. The hotel has three floors; in the 
first floor there three departments (Reception, store and Logistics), in the 
second floor there are three departments (Finance, HR and Sales/Marketing), while the third floor hosts the IT and Admin. Therefore, the following are part of the considerations during the design and implementation.

1. There are three routers connecting each floor (all placed in the server room in IT department).

2. All routers are connected to each other using serial DCE cable.

3. The network between the routers is 10.10.10.0/30 , 10.10.10.4/30 ,   10.10.10.8/30

4. Each floor is having one switch (placed in the respective floor).

5. Each floor is  having WIFI networks connected to laptops and phones.

6. Each department is having a printer.

7. Each department is expected to be in different VLAN with the following details

1st Floor

•	Reception- VLAN 80, Network of 192.168.8.0/24

•	Store-VLAN 70, Network of 192.168.7.0/24

•	Logistics- VLAN 60, Network of 192.168.6.0/24

2nd Floor

•	Finance- VLAN 50, Network of 192.168.5.0/24

•	HR-VLAN 40, Network of 192.168.4.0/24

•	Sales-VLAN 30, Network of 192.168.3.0/24


3rd Floor,

•	Admin- VLAN 20, Network of 192.168.2.0/24

•	IT-VLAN 10, Network of 192.168.1.0/24

8. Use OSPF as the routing protocol to advertise routes.

9. All devices in the network obtain IP address dynamically with their respective router configured as the DHCP server.
10. All the devices in the network communicate with each other.

11. Configure SSH in all the routers for remote login.

12. In IT department we added PC called Test-PC to port fa0/1 and use it to test remote login.


	

