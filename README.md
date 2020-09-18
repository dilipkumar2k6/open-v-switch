# Open vSwitch
![](https://www.openvswitch.org/assets/featured-image.jpg)
- Open vSwitch is a production quality, multilayer virtual switch licensed under the open source Apache 2.0 license.  
- It is designed to enable massive network automation through programmatic extension, while still supporting standard management interfaces and protocols (e.g. NetFlow, sFlow, IPFIX, RSPAN, CLI, LACP, 802.1ag).  
- In addition, it is designed to support distribution across multiple physical servers similar to VMware's vNetwork distributed vswitch or Cisco's Nexus 1000V. 

# Why Open vSwitch?
- Hypervisors need the ability to bridge traffic between VMs and with the outside world. 
- On Linux-based hypervisors, this used to mean using the built-in L2 switch (the Linux bridge), which is fast and reliable. So, it is reasonable to ask why Open vSwitch is used.
- The answer is that Open vSwitch is targeted at multi-server virtualization deployments, a landscape for which the previous stack is not well suited. 
- These environments are often characterized by highly dynamic end-points, the maintenance of logical abstractions, and (sometimes) integration with or offloading to special purpose switching hardware.




# Reference
https://www.openvswitch.org/
