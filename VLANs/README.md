VLAN Configuration
Create VLAN
Switch(config)# vlan 10
Switch(config-vlan)# name SALES
Assign VLAN to Port
Switch(config)# interface fa0/1
Switch(config-if)# switchport mode access
Switch(config-if)# switchport access vlan 10
