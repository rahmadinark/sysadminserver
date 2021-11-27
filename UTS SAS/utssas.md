# UTS Server Administration System - Laporan Instalasi Windows Server 2022

### Report by :

Rahmadina Oktaviana (1202190016)
___

Berikut soal UTS Sistem Administrasi Server :

![soal](asset/1.jpg)

Soal UTS dapat diaskes [disini.](https://yptorid-my.sharepoint.com/:w:/g/personal/aldo_ittelkom-sby_ac_id/EahwnD4AudVAqCDtSDN9JVsBTLMMU-hBAnMwq-2TthH9dA?e=gpexdw)

## Installation windows server 2022
---
### 1. Download ISO windows server 2022

- Berikut link untuk mendownload windows server 2022

    https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022
        
    - Download ISO windows server 2022

        ![](asset/2.jpg)
    
### 2. Open virtualbox untuk langkah awal instalasi pada virtualbox
    
- Create new virtual machine for windows server 2022

    ![](asset/3.jpg)

- Create name for virtual machine

    ![](asset/4.jpg)

- Setting RAM Virtual Machine

    ![](asset/5.jpg)
    
- Create Hard Disk
    
    ![](asset/6.jpg)
    
- Setting Hard Disk file type
    
    ![](asset/7.jpg)

- Setting storage on physical hard disk

    ![](asset/8.jpg)
    
- Setting location and size of Disk
    
    ![](asset/9.jpg)

- Hasil create virtual machine

    ![](asset/10.jpg)

### 3. Setting storage untuk select file windows server dan setting network 

- Setting storage

    ![](asset/11.jpg)

    ![](asset/12.jpg)

    ![](asset/13.jpg)


- Setting network

    ![](asset/14.jpg)
    

### 4. Open virtual machine

- Start virtual machine windows server 2022

    ![](asset/15.jpg)

- Instalasi wizzard windows server 2022

    ![](asset/16.jpg)

- Install windows server 2022

    ![](asset/17.jpg)

    - Select windows server 2022 desktop experience  
            
        ![](asset/18.jpg)

    - Accept license terms
            
        ![](asset/19.jpg)

    - Select install microsoft server advanced
            
        ![](asset/20.jpg)

    - Location installation of windows server 2022

         ![](asset/21.jpg)

    - Installing Microsoft Server Operating System

         ![](asset/22.jpg)

    - Create password 

         ![](asset/23.jpg)
    
    - Screen display lock desktop windows server 2022

         ![](asset/24.jpg)

    - Acsess the menu "Input "ctrl + alt + del" then enter the password created and wait for the configuration to load 

         ![](asset/25.jpg)
    
    - Go to the menu "Devices - Insert Guest Additions CD Image" 

         ![](asset/26.jpg)

         ![](asset/27.jpg)

         ![](asset/28.jpg)

    - Choose Install location

         ![](asset/29.jpg)

    - Choose Components

         ![](asset/30.jpg)

    - Install and reboot the machine then enter the password

         ![](asset/32.jpg)

         ![](asset/33.jpg)

    - Hasil

         ![](asset/34.jpg)

    - Windows server 2022 berhasil di install

         ![](asset/35.jpg)

## Instalasi Active Directory Domain Server

Ubah nama computer di windows powershell dengan mengetik > “rename-computer -Newname Server2022”

![](asset/36.jpg)

Kemudian masuk ke server manager pilih menu manage 

![](asset/37.jpg)

Kemudian pilih Add Roles and Features dan next

![](asset/38.jpg)

Pilih Role-Based or feature-based installation kemudian next

![](asset/39.jpg)

Setelah itu pilih select a server from the server pool

![](asset/40.jpg)

Lalu pilih active directory domain server

![](asset/41.jpg)

Kemudain klik add features

![](asset/42.jpg)

Kemudian ke features lalu centang Group Policy Management dan next

![](asset/43.jpg)

Kemudian install

![](asset/44.jpg)

## Installasi DNS

Kemudian install DNS server sama seperti menginstal domain 

![](asset/49.jpg)
![](asset/50.jpg)

## Installasi Net Framework 3.5

Setelah selesai install NET Framework 3.5

![](asset/51.jpg)

## Promote Server To A Domain

- Pilih network setting
  
    ![](asset/45.jpg)
- Pilih ip
  
    ![](asset/46.jpg)
- Setting ip static dengan ip baru
  
    ![](asset/47.jpg)
- Proses setting ip static berhasil
  
    ![](asset/48.jpg)
