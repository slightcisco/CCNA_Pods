# VLANs and Routing - Guide

- [ ] Open the file packet tracer file called Pod_2
- [ ] Create vlan 2 on SwitchA
- [ ] Give vlan 2 an IP address from the address range 192.168.11.0/24 and make sure the interface is up (not .1)
- [ ] Give PCB an address from the same range and amke its DG .1
- [ ] give vlan 1 an Address from the range 192.168.10.0/24 (not.1)
- [ ] Give PCA an address from the same range and set its DG to .1
- [ ] On switch A configure int fe0/1 to be an access port that only carries vlan 1 and Fe0/2 to only carry vlan 2
- [ ] make sure Switch A can ping PCA and PCB
- [ ] make sure PCA cannot ping PCB
- [ ] why cant they ping?
- [ ] On the router, configure g0/0/0 and g0/0/1 with the .1 address from the perspective ranges
- [ ] check if PCA can ping PCB
- [ ] What is this setup called
