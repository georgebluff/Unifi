# Unifi
## How to live packet capture with Unifi Dream Machine & Wireshark

Using Wireshark with unifi-os shell & tcpdump </br> https://www.youtube.com/watch?v=uGpoCs2TdG4


- unifi-os shell
- install samba /smb
- add samba/smb user
- create /tmp SMB share on local drive (12GB for UDM)
- initiate tcpdump > out to /tmp/tcpdump.pcap
- launch wireshark > open tcpdump.pcap
