/interface bridge
add name=bridge1 protocol-mode=none vlan-filtering=yes
/interface bridge port
add bridge=bridge1 interface=ether2
add bridge=bridge1 interface=ether3
