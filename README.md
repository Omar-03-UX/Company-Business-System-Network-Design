# Company Business System Network Design
# Hotel Network Design
<h2>Description</h2>

In this lab I will build a Company Business System Network Design

Step 1: Physical Network Topology
Design the physical layout of the network, considering the three floors and the departments on each floor.

Step 2: Hierarchical Model
Implement a hierarchical model with Core, Distribution, and Access layers.

Step 3: VLAN Design and Subnetting
Assign VLANs to each department.
Subnet the base network (172.16.1.0) to allocate IP addresses to each department.
Create a wireless VLAN for each department.

Step 4: Internet Connectivity
Connect each router to two ISPs for redundancy.
Assign the provided static public IP addresses to the router interfaces connected to ISPs.
Implement OSPF for dynamic routing between routers.

Step 5: Device Configuration
Configure basic settings for all devices (hostnames, passwords, banners, disable IP domain lookup).
Configure IP addresses for multilayer switches and routers.
Implement inter-VLAN routing on multilayer switches.

Configure DHCP servers in the server room for dynamic IP assignment.

Step 6: Security Measures
Configure SSH on routers and multilayer switches for remote login.
Implement port security on the Finance and Accounts department's switchports.
Configure PAT on routers with ACL rules for internet access.

Step 7: Testing and Verification
Test communication between devices in different departments.
Verify OSPF routing tables on routers and multilayer switches.
Ensure DHCP is assigning IP addresses correctly.
Verify port-security settings on the Finance and Accounts department.

Step 8: Documentation
Document the logical design.

Document the network design, configurations, and any troubleshooting steps for future reference.
<br />

<h2>Languages and Utilities Used</h2>

- <b>CLI packet tracer</b> 
  
<h2>Environments Used </h2>
