<h2 align="center">3 floors hotel managment topology</h2>

```
  1- the hotel has 3 floors and 3 departments in each floor:
    1st Floor: * Reception, VLAN 80, Network address 192.168.8.0/24
               * Store, VLAN 70, Network address 192.168.7.0/24
               * Call Center, VLAN 60, Network address 192.168.6.0/24
  
    2nd Floor: * Finance, VLAN 50, Network address 192.168.5.0/24
               * HR, VLAN 40, Network address 192.168.4.0/24
               * Sales, VLAN 30, Network address 192.168.3.0/24

    3rd Floor:
               * Admins, VLAN 20, Network address 192.168.2.0/24
               * IT, VLAN 10, Network address 192.168.1.0/24
```

<img width="1046" height="519" alt="1" src="https://github.com/user-attachments/assets/a7678de4-6de8-4ff7-bcbe-550b43197d05" />  

<h4>Each floor is served by its own router functioning as the DHCP server, with inter‑VLAN routing enabled on every router using a `Router‑on‑a‑Stick` configuration.</h4>
<br/>

```devices in first floor is assigned IPs from the dhcp server of the first floor ```  <br/>

<img width="726" height="704" alt="2-2" src="https://github.com/user-attachments/assets/3875040c-c193-4819-b050-c5992bbc46e6" />  

```devices in second floor is assigned IPs from the dhcp server of the second floor ```<br/>  

<img width="1058" height="634" alt="3" src="https://github.com/user-attachments/assets/8d41eb9b-3360-40e1-8824-1aa755f0acfb" />  

```devices in third floor is assigned IPs from the dhcp server of the third floor ```<br/>  

<img width="1435" height="1035" alt="4" src="https://github.com/user-attachments/assets/f0fdff45-f35f-4273-8ade-7fa62e323afe" />  

``` OSPF protocol is configured on the routers, the letter O in the picture ensures that the router learned these networks from OSPF ``` <br/> 

<img width="991" height="1091" alt="5" src="https://github.com/user-attachments/assets/2f521ef4-9a0d-43c0-b2cf-6b9ff44599c4" />  


``` Hosts inside the same floor can communicate ```  <br/>

<img width="1805" height="514" alt="6" src="https://github.com/user-attachments/assets/72c1af87-bd3b-4002-8aa1-1c4d4b1f95e3" />  

```Hosts in different floors can also communicate ``` <br/> 

<img width="1848" height="721" alt="7" src="https://github.com/user-attachments/assets/4f889460-b6e2-4ae3-ad44-9acf7f7a91d8" />  <br/>

<h2>everything is connected smothly and network is running</h2>
<h1>by, Sayfullah Saied</h1>


