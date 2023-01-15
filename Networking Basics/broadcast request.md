When a device wants to communicate with another device on a LAN (Local Area Network), it may use a broadcast request to ask for the physical address (MAC address) of the destination device.
A broadcast request is a message that is sent to the broadcast address of the LAN and is received by all devices on the network. The device that has the IP address being looked up will respond with its MAC address.

For example, when a device wants to communicate with another device on a LAN, it can use ARP (Address Resolution Protocol) to broadcast a request on the network asking for the physical address (MAC address) of a specific IP address. The device with that IP address will respond with its physical address (MAC address), allowing the two devices to communicate.

Broadcast messages are also used for other network services such as DHCP (Dynamic Host Configuration Protocol) to assign IP addresses to devices, RARP (Reverse Address Resolution Protocol) to map a physical address to an IP address, and many others.

It's worth noting that broadcasting can cause a lot of traffic on a network, and it's not a very efficient way of communication. This is why multicast and unicast were introduced.
