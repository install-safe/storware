Storeware <br>
https://storware.eu   TRY NOW 填資料獲取iso 載點與郵件會收到license.key 60天Trial <br>
VM 規格  10 vCPU , 12 GB memory , Disk1 30 GB , Disk2 200GB up , nic x1  <br>
iso 開機安裝 , 改IP 
https://ip-address   admin/密碼是vPr0tect   , console/ssh root/密碼是vPr0tect<br>

[root@storware-backup-and-recovery /]# ls -lat<br>
total 24
drwxr-xr-x.   8 vprotect vprotect   96 Apr  1 10:53 vprotect_data<br>

 /]# ls -l /vprotect_data/<br>

drwxr-xr-x. 2 vprotect vprotect  20 Apr  1 09:30 backups  本身就會建<br>
drwxr-xr-x. 3 vprotect vprotect  44 Apr  1 10:08 hyperv   這是後來透過configuration wizard  所產生的目錄 , 本例用於local filesystem<br>
drwxr-xr-x. 2 vprotect vprotect   6 Apr  1 10:38 import   還原時的stage會放在這<br>
drwxr-xr-x. 2 vprotect vprotect  20 Apr  1 10:53 proxmox  這是後來透過configuration wizard  所產生的目錄 , 本例用於local filesystem<br>
drwxr-xr-x. 4 vprotect vprotect 124 Apr  1 10:57 staging  備份時的stage會放在這<br>
drwxr-xr-x. 3 vprotect vprotect  63 Apr  1 09:55 vcenter01 這是後來透過configuration wizard  所產生的目錄 , 本例用於local filesystem<br>
