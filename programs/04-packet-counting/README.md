This program performs packet parsing and counts the number of VLAN, IPv4, ICMP, TCP and UDP packets. We store the packet count in eBPF map named “xdp_hdr_map”  at indexes 0, 1, 2, 3, and 4 for VLAN, IPv4, ICMP, UDP and TCP, respectively.