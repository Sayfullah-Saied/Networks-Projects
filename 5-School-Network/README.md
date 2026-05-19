<h2 align="center">JAKARTA School Network Topology</h2>
<br>
#By, Sayfullah<br>
<hr>
<h4 align="center">#the School has Two floors:</h4>

```
Floor 1 : 
          - Lecturers Department: VLAN 50, Network ADD: 192.168.5.0/24
          - Assistants Department: VLAN 70, Network ADD: 192.168.7.0/24
          - ART-LABS: VLAN 60, Network ADD: 192.168.6.0/24
          - Science-LAABS: VLAN 80, Network ADD: 192.168.8.0/24
```
```
Floor 2 : 
          - Administrators Department: VLAN 10, Network ADD: 192.168.1.0/24
          - Affairs Department: VLAN 20, Network ADD: 192.168.2.0/24
          - IT Department: VLAN 40, Network ADD: 192.168.4.0/24
          - servers-Room: VLAN 30, Network ADD: 192.168.3.0/24
```
#OSPF protocol running on routers to connect the floors<br>
#The server room includes a DHCP server for automatic IP assignment and a web server for hosting the school’s website<br>
#The network uses router‑on‑a‑stick InterVLAN routing to enable traffic flow between different VLANs.
<br>
<img width="958" height="649" alt="1" src="https://github.com/user-attachments/assets/1fb430bd-66a4-486d-ba99-441ccf8ca644" />
