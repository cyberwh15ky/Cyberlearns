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








