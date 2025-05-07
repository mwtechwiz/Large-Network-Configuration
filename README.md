<p align="center">
<img src="https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT20.jpg?raw=true" alt="Traffic Examination"/>
</p>

<h1>Large Network Configuration</h1>

This project demonstrates the configuration of a large enterprise network in Cisco Packet Tracer, consisting of:
- 20 PCs
- 6 Access Switches
- 4 Multilayer Switches
- 4 Servers (DHCP, DNS, HTTP)
- 3 Routers (connecting 3 Sites)

The setup includes dynamic IP allocation, inter-VLAN routing, and cross-site communication. <br />


<h2>Environments and Technologies Used</h2>

- Cisco Packet Tracer
- Cisco IOS

<h2>Operating Systems Used </h2>

- Windows 11

<h2>High-Level Steps</h2>

 1. Device Placement
- Place all routers, switches, servers, and PCs in logical groups by site.

 2. Cabling
- Use straight-through cables for end device connections.
- Use crossover cables for switch-router connections and switch-switch trunk links.
- Use serial DCE/DTE connections between routers.

 3. IP Configuration
- Assign static IPs to routers, servers, and management interfaces.
- Use DHCP servers for dynamic IPs on PCs.

 4. VLAN and Inter-VLAN Setup
- Enable routing on multilayer switches for inter-VLAN communication.

5. Routing Configuration
- Configure routing tables on routers.
- Ensure all routers can reach each other's subnets.

 6. Server Setup
- Configure DHCP to serve client PCs.
- Configure DNS (e.g., Bing.com resolves to 192.168.5.2).
- Configure HTTP server (e.g., Google.com on 192.168.5.3).

 7. Testing
- Ping across VLANs and subnets.
- Use web browsers from PCs to access HTTP server.

<h2>Actions and Observations</h2>

<p>
  - Place all routers, switches, servers, and PCs in logical groups by site.
 
![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT1.jpg)

- Use straight-through cables for end device connections.
- Use crossover cables for switch-router connections and switch-switch trunk links.
- Use serial DCE/DTE connections between routers.
  
![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT2.jpg)
</p>
<p>
</p>
<br />

<p>


Assign static IPs to routers, servers, and management interfaces. Using CLI command "show ip inter brief" we see the table showcasing ports and their connectivity.
  
![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT3.jpg)
![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT4.jpg)
![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT5.jpg)
![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT%207.jpg)
![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/Pt10.jpg)
</p>
<p>
 
- Configure DHCP to serve client PCs.
- Configure DNS (e.g., Bing.com resolves to 192.168.5.2).
- Configure HTTP server (e.g., Google.com on 192.168.5.3).

![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT11.jpg)
 ![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT12.jpg)


 ![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT13.jpg)
 ![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT14.jpg)
 ![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT15.jpg)
  ![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT22.png)


- Router command "show ip route" showcases the routing table with directly connected routes.
- Here we are showcasing successful packets traveling from router to router. You can see the table in the right corner.

![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT19.jpg)
![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT20.jpg)
![image](https://github.com/mwtechwiz/Large-Network-Configuration/blob/main/PT%2021.jpg)

 
</p>
<br />
