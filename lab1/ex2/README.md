# Ex 2 - Basic Autimatic Configuration

A local lan with 2 pcs, a default gateway that also operates as a DHCP
server.
The assignment is: to manually configure r1 to act as DHCP server and
the 2 pcs to request an IP address from it.

- r1 is set up with the IP address 192.168.100.30/28. It should use
  the network 192.168.100.16/28 as the address pool

> 192.168.100.17 - 192.168.100.29 (.31 bc, .30 server, .16 network)

- the DNS server can be the server used by the host machine (this has
  to be set in all the pc of the lab)

- the default gateway is r1

- pc1 should be configured using the interfaces file

- pc2 should be configured using the **dhclient** command
