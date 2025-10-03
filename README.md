# Internet Protocols

#### IPv4 (Internet Protocol version 4)
32-bit numerical addresses represented in a dotted-decimal format (192.168.1.54). Each section, or octet, consists of 8 bits and can range from 0 to 255. This allows for a total of approximately 4.3 billion unique addresses.

#### IPv6 (Internet Protocol version 6)
128-bit addresses represented in a hexadecimal format (2001:0db8:85a3:0000:0000:8a2e:0370:7334). The longer format allows for a significantly larger number of unique addresses, approximately 340 undecillion (3.4×10^38). Divided into eight groups of four hexadecimal digits separated by colons. Leading zeroes within a group can be and omitted, and consecutive groups of zeroes can be represented by a double colon (::). IPv6 introduces improvements in security, auto-configuration, and other features. Not compatible with IPv4.


#### MAC Addresses (Layer 2 - Data Link Layer)
Media Access Control (MAC) addresses are unique identifiers assigned to Network Interface Controllers (NICs) of network devices. It is permanent address assigned by the manufacturer that is stored in the device's firmware or Read-Only Memory (ROM). Used at the data link layer of the OSI model to ensure traffic is delivered to the correct device within the local network.

Typically 48 bits in length and expressed as a sequence of six pairs of hexadecimal digits separated by colons or hyphens (00:1A:2B:3C:4D:5E) with the first three pairs of digits identifying the manufacturer of the NIC, while the last three pairs provide a unique ID for the specific device.
MAC addresses allow devices to communicate with each other within a local LAN. Encapsulated within Ethernet frames that contain the source and destination MAC addresses, routers and switches use these MAC addresses to forward the data to the appropriate destination.


## TCP, UDP, Three-Way Handshake (Layer 4 - Transport Layer)

#### Transmission Control Protocol (TCP)
A connection-oriented protocol that provides reliable, ordered, and error-checked delivery of data packets over an IP network. It guarantees that data sent from one device is received correctly by the destination device. TCP achieves this reliability through mechanisms such as acknowledgement, retransmission, and flow control. It breaks data into smaller packets, assigns sequence numbers to them, and ensures they are reassembled correctly at the receiving end. TCP is widely used for applications that require guaranteed delivery, such as web browsing, email, file transfer, and remote login.

#### User Datagram Protocol (UDP)
A connection-less protocol that does not provide the same level of reliability as TCP. Simpler and more lightweight, making it suitable for applications that can tolerate some data loss or delay. UDP does not establish a connection or guarantee delivery of packets. It simply sends data packets from one device to another without waiting for acknowledgements or retransmissions. UDP is commonly used for real-time applications like streaming media, online gaming, DNS (Domain Name System), and VoIP (Voice over IP).


