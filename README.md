# netdiscover
In the context of IP (Internet Protocol), "CIDR" stands for Classless Inter-Domain Routing. It is a method used to allocate and manage IP addresses and their routing on the Internet. CIDR notation is used to represent a network or subnet's IP address and its associated prefix length.

CIDR notation consists of the IP address followed by a forward slash (/) and the number of bits that represent the network prefix. For example, 192.168.0.0/24 represents a network with an IP address of 192.168.0.0 and a prefix length of 24 bits, indicating that the first 24 bits (or the first three octets) are the network portion.

The CIDR notation allows for more flexible and efficient allocation of IP addresses compared to the older system of class-based addressing. It enables network administrators to divide IP address space into smaller subnets, providing more precise control over routing and addressing.

step 1: Open cmd prompt in system

step 2: Type ipconfig for windows

step 3: Identify the CIDR format of ip

step 4: run the tool in windows and enter CIDR format ex: 192.168.0.0/24

step 5: wait for  few minuites too see the ip adresses that are live in network


The "netdiscover" tool is used to scan a local network and discover devices connected to it. It sends ARP (Address Resolution Protocol) requests to the network, and based on the responses received, it can identify active hosts along with their IP and MAC addresses.

# Option File

file option is used to exit the tool from running

# Option Help 

Help option is to display the developer info and contact info.
