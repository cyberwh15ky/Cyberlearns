set network interface ethernet ethernet1/3 layer3 ip 192.168.10.60/24
set network profiles interface-management-profile mgmt-http https yes
set network profiles interface-management-profile mgmt-http http yes
set network profiles interface-management-profile mgmt-http ping yes
set network interface ethernet ethernet1/3 layer3 interface-management-profile mgmt-http
commit

set zone trust-L3 network layer3 ethernet1/3
set network virtual-router default interface ethernet1/3
commit




--------------------------------------------------------------------------------------------------------------


set deviceconfig system ip-address 172.16.7.195 netmask 255.255.252.0 default-gateway 172.16.4.1


