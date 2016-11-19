# Tips

vsFtp server 

```
sudo nano /etc/vsftpd.conf
anonymous_enable=NO
pasv_enable=YES
pasv_min_port=1024
pasv_max_port=1048
pasv_address=<Public IP of your instance> 
```