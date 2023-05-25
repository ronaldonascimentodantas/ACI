# ACI CLI

Usesful ACI CLI commands. For leaf switches and APIC Controllers.

## APIC CLI

    acidiag avread
    acidiag cluster
    acidiag fnvread
    avread
    show oob-mgmt
    show controller
    df -k
    show version
    show firmware upgrade status
    attach SWITCH-NAME
    fabric <nodeid> <swich-command>
    fabric <nodeid1>-<nodeid2> <swich-command>
          e.g.: fabric 101 show version 

    show runn leaf <leafid>
    show run template port-channel <vpc_pol-grp>
    fabric <nodeid> show interface desc
    show tenant <tenant name> application <ap> endpoints
    show endpoints mac <mac-address>
    show endpoints vlan <vlanid>

    show tenant <tenantname> detail
    show tenant <tenant name> epg <epgname> details
    fabric <nodeid> show port-channel database
    fabric <nodeid> show port-channel summary
    fabric <nodeid> show mac address-table interface port-channel <POn>

## LEAF CLI

    show version
    show interface 1/n 
    show interface brief
    show interface status
    show interface description
    show interface 1/n transceiver detail
    show hardware
    show module
    show environment
    show clock
    show port-channel summary
    show vpc brief
    show cdp neighbor
    show lldp neighbor
    show endpoint
    show endpoint interface <int>
    show endpoint [summary|address|interface|vlan|vrf]
    show vrf
    show ip route vrf <vrfname>
    show ip route <prefix> vrf <vrfname>
    iping -V <vrfname> <ipaddress>
