######20260831  
<img width="763" height="395" alt="image" src="https://github.com/user-attachments/assets/95211025-72b7-4a0e-a9e5-7eec04e56998" />  
[prisma-sd-wan-instant-on-network-ion-1200.pdf](https://github.com/user-attachments/files/31626716/prisma-sd-wan-instant-on-network-ion-1200.pdf)  


Putty:  
- Serial  
- COM xx  
- Speed:11520  

Default Account:  
elem-admin  
hackle628)bags  

<img width="157" height="68" alt="image" src="https://github.com/user-attachments/assets/7afaa579-2198-4ef3-8f97-c0d805144ec1" />  


<img width="317" height="115" alt="image" src="https://github.com/user-attachments/assets/7456cc87-e18c-4e4f-89e4-e30bffa10c6d" />  



第一步: 先上網，之後會出現 多次自動還原原廠  
dump interface status all  
<img width="401" height="226" alt="image" src="https://github.com/user-attachments/assets/81ef4058-f72a-409a-bb07-868b3f28ee0d" />  
<img width="382" height="408" alt="image" src="https://github.com/user-attachments/assets/af45d489-75f6-48c4-9cff-c4928c475a5f" />  

config interface <介面名稱> ip static address=<IP地址/遮罩> gw=<預設閘道> dns=<DNS伺服器>  
config interface 1 ip static address=192.168.129.12/24 gw=192.168.129.254 dns=1.1.1.1  
<img width="344" height="148" alt="image" src="https://github.com/user-attachments/assets/2066a776-8220-4e20-9d71-12528b678492" />  

dump controller status
<img width="940" height="34" alt="image" src="https://github.com/user-attachments/assets/4effed37-90ad-4fdd-ad45-e11dc4b5f3b2" />  
<img width="938" height="98" alt="image" src="https://github.com/user-attachments/assets/674ebf9b-64b3-48b4-850c-797b23668aa5" />  


Activate to CSM and SCM
<img width="935" height="518" alt="image" src="https://github.com/user-attachments/assets/eca67fec-9fc4-45a8-b109-5557fdc01906" />

<img width="786" height="524" alt="image" src="https://github.com/user-attachments/assets/ae50413e-bde9-4f9b-8f92-efa2a2a4688b" />  
<img width="787" height="509" alt="image" src="https://github.com/user-attachments/assets/d03081aa-65eb-4298-ad47-1c8f9a170875" />  ######August 31, 2026
<img width="763" height="395" alt="image" src="https://github.com/user-attachments/assets/95211025-72b7-4a0e-a9e5-7eec04e56998" />
[prisma-sd-wan-instant-on-network-ion-1200.pdf](https://github.com/user-attachments/files/31626716/prisma-sd-wan-instant-on-network-ion-1200.pdf)




Putty:
- Serial number
- COM xx
- Speed: 11520


Default Account:
elem-admin
hackle628) bags


<img width="157" height="68" alt="image" src="https://github.com/user-attachments/assets/7afaa579-2198-4ef3-8f97-c0d805144ec1" />




<img width="317" height="115" alt="image" src="https://github.com/user-attachments/assets/7456cc87-e18c-4e4f-89e4-e30bffa10c6d" />






Step 1: First, access the internet. Then, you will see "Multiple automatic factory resets."
Status of all dump interfaces
<img width="401" height="226" alt="image" src="https://github.com/user-attachments/assets/81ef4058-f72a-409a-bb07-868b3f28ee0d" />
<img width="382" height="408" alt="image" src="https://github.com/user-attachments/assets/af45d489-75f6-48c4-9cff-c4928c475a5f" />


Configure interface <interface name> with static IP address: <IP address/mask>, gateway: <default gateway>, and DNS server: <DNS server>.
Configure interface 1 with a static IP address of 192.168.129.12/24 and a gateway of 192.168.129.254, using DNS servers 1.1.1.1.
<img width="344" height="148" alt="image" src="https://github.com/user-attachments/assets/2066a776-8220-4e20-9d71-12528b678492" />


Status of the dump controller
<img width="940" height="34" alt="image" src="https://github.com/user-attachments/assets/4effed37-90ad-4fdd-ad45-e11dc4b5f3b2" />
<img width="938" height="98" alt="image" src="https://github.com/user-attachments/assets/674ebf9b-64b3-48b4-850c-797b23668aa5" />




Activate CSM
<img width="935" height="518" alt="image" src="https://github.com/user-attachments/assets/eca67fec-9fc4-45a8-b109-5557fdc01906" />

Activate SCM
<img width="786" height="524" alt="image" src="https://github.com/user-attachments/assets/ae50413e-bde9-4f9b-8f92-efa2a2a4688b" />
<img width="787" height="509" alt="image" src="https://github.com/user-attachments/assets/d03081aa-65eb-4298-ad47-1c8f9a170875" />






