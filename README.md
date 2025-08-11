# Network-Security
Packet Decoding and IP Header Modification


Developed a C++ program to modify source IP addresses in captured packets (PCAP format) from Wireshark to adesignated 18.X.X.X range.

Recalculated and validated IP header checksums to ensure data integrity using packet-level verification and verified output accuracy by comparing modified packets with original captures in Wireshark, including MAC address validation.

Results: 
1) The IP checksum has been validated at the xyz.pcap (output file) indicating that it has been calculated correctly and ensures the integrity of the packets.
2) Managed to modify all captured source IP Address to 18.X.X.X range.
3) MAC Address Validation sucessfull - indicating similar MAC Address betweeen original and modified .pcap file. 
