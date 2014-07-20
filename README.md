wheelspin
=========

hackscripts used to do fast fire-and-forget kind of use `lxc` containers

network
-------

statics for now. improvement by using dnsmasq?

```
lxc.network.type = veth
lxc.network.flags = up
lxc.network.link = tor0
lxc.network.ipv4 = 192.168.2.3/24
lxc.network.ipv4.gateway = 192.168.2.1
```


