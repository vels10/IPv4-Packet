# IPv4-Packet

## In this Code change ur File name(Hex value for Ipv4 Packet copied fron Wireshark),(In this it will be "arp" ).It's a IPv4 Header Packet Parsing a different segement like

## Version :
Version no. of Internet Protocol used (e.g. IPv4).

## Header Length:
Internet Header Length; Length of entire IP header.

## DSCP:
Differentiated Services Code Point; this is Type of Service.

## ECN:
Explicit Congestion Notification; It carries information about the congestion seen in the route.

## Total Length:
Length of entire IP Packet (including IP header and IP Payload).

## Identification:
If IP packet is fragmented during the transmission, all the fragments contain same identification number. to identify original IP packet they belong to.

## Flags:
As required by the network resources, if IP Packet is too large to handle, these ‘flags’ tells if they can be fragmented or not. In this 3-bit flag, the MSB is always set to ‘0’.

## Fragment Offset:
This offset tells the exact position of the fragment in the original IP Packet.

## Time to Live:
To avoid looping in the network, every packet is sent with some TTL value set, which tells the network how many routers (hops) this packet can cross. At each hop, its value is decremented by one and when the value reaches zero, the packet is discarded.

## Protocol:
Tells the Network layer at the destination host, to which Protocol this packet belongs to, i.e. the next level Protocol. For example protocol number of ICMP is 1, TCP is 6 and UDP is 17.

## Header:
Checksum − This field is used to keep checksum value of entire header which is then used to check if the packet is received error-free.

## Source Address:
32-bit address of the Sender (or source) of the packet.

## Destination Address:
32-bit address of the Receiver (or destination) of the packet.

## Options:
This is optional field, which is used if the value of IHL is greater than 5. These options may contain values for options such as Security, Record Route, Time Stamp, etc.
