
Technologies Implemented
* Use Cisco Packet Tracer to design and implement the network solution.
* Use a hierarchical model providing redundancy in the network.
* Both HQ and Branch routers are expected to be connected using a serial connection.
* As mentioned earlier, for network cost-effectiveness, each site is expected to have one core router, two multilayer switches, and several access switches connecting each department.
* Each department is required to have a wireless network for the users.
* Every department in HQ is estimated to have around 60 users while in Branch is estimated to be 30 users.
* Each department should be in a different VLAN and a different subnetwork.
* Provided a base network of 192.168.100.0, and carry out subnetting to allocate the correct number of IP addresses to each department.
* The company network is connected to the static, public IP addresses (Internet Protocol) 195.136.17.0/30, 195.136.17.4/30, 195.136.17.8/30, and 195.136.17.12/30 connected to the two Internet providers.
* Configure basic device settings such as hostnames, console password, enable password, banner messages, and disable IP domain lookup.
* Devices in all the departments are required to communicate with each other with the respective multilayer switch configured for inter-VLAN routing.
* The Multilayer switches are expected to carry out both routing and switching functionalities and thus will be assigned IP addresses.
* All devices in the network are expected to obtain an IP address dynamically from the dedicated DHCP servers located in the server room.
* Devices in the server room are to be allocated IP addresses statically.
* Use OSPF as the routing protocol to advertise routes both on the routers and multilayer switches.
* Configure default static routing to enable routers and multilayer switches to forward any traffic that does not match routing table entries. Use next-hop IP addresses.
* Configure SSH in all the routers and layer three switches for remote login.
* Configure port-security for the server site department switch to allow only one device to connect to a switch port, use sticky method to obtain mac-address and violation mode shutdown.
* Configure the extended ACL rule together with site-to-site  VPN (IPSec VPN) to create a tunnel and encrypt  communication between HQ and the Branch network.
* Configure PAT to use the respective outbound router interface IPv4 address, and implement the necessary ACL rule.
* Test Communication, ensure everything configured is working as expected.

