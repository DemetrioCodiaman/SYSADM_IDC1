

|  SCHOOL OF INFORMATION AND TECHNOLOGY |  |  |
| ----- | :---- | :---: |
| NAME: Demetrio L. Codiaman | DATE PERFORMED: 11/09/2024 |  |
| Section: IDC1 | DATE SUBMITTED: 11/09/2024 |  |

1. # SYSADM1 – Managing Services in Linux

2. # Requirement: 

* A virtual machine running Linux 

![][image1]

Complete this lab as follows: 

1. Use the service –status-all command to list all active and inactive services.

List down active and inactive services in the table below. Provide five (5) services for each column.

| Active | Inactive |
| ----- | ----- |
| apport | bluetooth |
| Alsa-utils | anacron |
| cron | apparmor |
| cups | console-setup.sh |
| dbus | Cryptdisks-early |

SS: 
![image](https://github.com/user-attachments/assets/535317ae-eea6-4844-ae5e-06a16802199c)

2.  start

Ex. sudo systemctl start httpd

3. Check the status of the Bluetooth service. What is its status?

SS: 
![image](https://github.com/user-attachments/assets/79efa88f-7949-409b-90d3-0db29f78b32a)

4. Check the status of the cups services. 

Since when was it running?

- Its been running since Wednesday 2024-09-11 at 09:11:45 UTC.

SS:  ![image](https://github.com/user-attachments/assets/98f6d45e-8a17-4d4c-8357-c6b611a11504)



5. Stop cups services.  
   6. Verify if the service was stopped. 

![image](https://github.com/user-attachments/assets/5e7bb40e-1ec0-4497-b7ae-1e56f53d818f)

7. Restart the cups services  
   8. Verify if the service was restarted. 

![image](https://github.com/user-attachments/assets/dcbe39eb-8c5c-4ff9-adcf-bd58106a8ecd)
