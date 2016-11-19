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

security

```bash
sudo adduser sammy
sudo mkdir /home/sammy/ftp
sudo chown nobody:nogroup /home/sammy/ftp
sudo chmod a-w /home/sammy/ftp
sudo mkdir /home/sammy/ftp/files
sudo chown sammy:sammy /home/sammy/ftp/files

sudo nano /etc/vsftpd.conf
chroot_local_user=YES
user_sub_token=$USER
local_root=/home/$USER/ftp
```