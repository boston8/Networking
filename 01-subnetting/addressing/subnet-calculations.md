# Subnet Calculations

## Starting Network

`192.168.10.0/24`

Total addresses: 254 usable host addresses (256 total)

Calculation: There are 8 bits left for the host portion of the address so there are 2^8 total addresses left. However, two of these IP addresses are reserved. The first is the network ID (192.168.10.0) and the last is the broadcast address (192.168.10.255). This means there are 254 usable addresses. The subnet mask is 255.255.255.0. This network uses class C addresses as there are 8 host ID bits and 24 network ID bits.

---

## Development

Required hosts: 50

Required subnet size: 64

Chosen prefix: /26

Calculation: I need 50 addresses, so my next available block using power of 2's is 64. This is 2^6, which means there are 6 bits for the host portion of the address and 26 bits for the network ID portion. The first subnet contains 64 consecutive addresses. The subnet mask is 255.255.255.192 (255.255.255.11000000) and the CIDR notation is /26. 

Network: 192.168.10.0

First usable: 192.168.10.1

Last usable: 192.168.10.62

Broadcast: 192.168.10.63

---

## Administration

Required hosts:

Required subnet size:

Chosen prefix:

Calculation:

Network:

First usable:

Last usable:

Broadcast:

---

## Sales

Required hosts:

Required subnet size:

Chosen prefix:

Calculation:

Network:

First usable:

Last usable:

Broadcast:

---

## Support

Required hosts:

Required subnet size:

Chosen prefix:

Calculation:

Network:

First usable:

Last usable:

Broadcast: