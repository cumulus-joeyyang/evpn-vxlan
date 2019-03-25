These files include playbooks and configurations for the cldemo-vagrant topology to be used for evpn vxlan scenarios.

1 - Pure L2 VXLAN with routing on Edge device and Centrilized VXLAN setup with routing on Exit leaf

2 - Asymmetric EVPN

3 - Symmetric EVPN

4 - Symmetric EVPN with Type 5

5 - Asymmetric EVPN with Type 5

6 - All in one with three VRF for each secnario


cumulus@oob-mgmt-server:~$ git clone https://github.com/cumulus-joeyyang/evpn-vxlan.git

cumulus@oob-mgmt-server:~$ cd evpn-vxlan/

cumulus@oob-mgmt-server:~/evpn-vxlan$ ansible-playbook pushscenario.yml -e s=1

