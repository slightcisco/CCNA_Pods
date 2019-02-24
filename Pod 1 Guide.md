# Basic LAN Operations - Guide

- [ ] Add 2 2960's
- [ ] Connect them using the correct cable type both on port Gigabit 0/1
- [ ] Rename the switches SwitchA and SwitchB in the Packet Tracer logical topology pane
- [ ] Also change the hostname to match in CLI
- [ ] Give the switches an enable password of cisco (whats the difference between enable password and enable secret)
- [ ] Assign both the switches an IP address in the network 192.168.10.0/24 onto the interface vlan 1 and make sure vlan 1 is up
- [ ] Ensure the interfaces connected are up with a show command
- [ ] The switches should now be able to ping eachother - test
- [ ] Add a PC connected to each of the switches and name them PCA and PCB accrdingly in the logical view
- [ ] Connect both the PCs to the switches on port Fe0/1 on the switch and Fe0 on the PC
- [ ] Use the desktop view on the PCs to assign them and IP in the same network as the switches
- [ ] Ensure the interfaces that the PCs are connected to on the switch are up with a show command
- [ ] PCA and PCB should be able to ping now - test
- [ ] If the ping doesnt hit first time, but hits from then on, try work out why (think about the OSI model and the different types of addresses)
- [ ] Now add a server to SwitchB
- [ ] Also give it an IP address in the same network as above
- [ ] Ensure that the web server is active
- [ ] Try reach the web server from PCB and then PCA
