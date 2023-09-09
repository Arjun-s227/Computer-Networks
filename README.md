# Automated-Path-Computation-SDN-

## Overview

Developed a RYU controller program to discover the network topology, calculate link costs based on traversed
time,and compute optimal paths for all host pairs for tree network topology of 10 nodes using Mininet and RYU.

Implemented user interaction for connection requests, considering source, destination, service type (IPv4 or MAC),and
bandwidth. Generated and applied configuration updates on intermediate switches along the path.



## Demo
Output after network discovery

![image](https://github.com/ShubhamPednekar19/Automated-Path-Computation-SDN-/assets/83055678/0341c003-328e-4cbf-8a89-0f72710eb797)

Command to run on Mininet
![image](https://github.com/ShubhamPednekar19/Automated-Path-Computation-SDN-/assets/83055678/e9ddb48e-01fa-433e-a400-a232d43c0dda)

For all pairs shortest paths I created ShortestPath.py which when run using ryu-manager alongside mininet gives all pairs of mac-addresses and the shortest path between them. A sample output is-
![image](https://github.com/ShubhamPednekar19/Automated-Path-Computation-SDN-/assets/83055678/51ce5fa0-0003-41ad-9eba-e351760eda33)

