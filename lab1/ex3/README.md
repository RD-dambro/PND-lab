# Ex 3 - Manual Configuration: Two LANs

Two lan, both with 2 pc and one router. Then, another lan that joins
the two routers with a border gateway (r0).  The assignment is: to
configure the 4 pc and the three routers so that the two lans are
reachable and all can reach the Internet.

- You have to use the 172.16.0.0/16 network and assign subnetworks to
  all the LANs in the topology. Think about the most suitable approach.

- r0 has to be the default gateway of the whole network. It is already
  set up to act as the default gateway. It is connected to the
  internet via eth0.

- r1 and r2 have to be the default gateways for "lan1" and "lan2",
  respectively. They have to have a default route towards r0 and
  static routes to reach lan1 or lan2. To set up static routes you can
  use the ip route command (man ip-route).

- the DNS server can be the server used by the host machine (this has
  to be set in all the pcs of the lab) or 8.8.8.8

- the PCs can be configured as you prefer
