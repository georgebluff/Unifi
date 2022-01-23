# Unifi
## How to live packet capture with Unifi Dream Machine & Wireshark

<br/>
![This is an image](https://raw.githubusercontent.com/georgebluff/Unifi/main/ubiquiti-dream-machine.png) <br/><br/>


Steps
- unifi-os shell
- install samba /smb
- add samba/smb user
- create /tmp SMB share on local drive (12GB for UDM)
- initiate tcpdump > out to /tmp/tcpdump.pcap
- launch wireshark > open tcpdump.pcap

Links:
Using Wireshark with unifi-os shell & tcpdump </br> https://www.youtube.com/watch?v=uGpoCs2TdG4
