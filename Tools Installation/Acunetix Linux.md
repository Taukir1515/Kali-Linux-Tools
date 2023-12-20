- File for Acunetix Linux is "Acunetix-15.3-linux.rar".

- Extract it.

- Open /etc/hosts file with any text editor.
```
mousepad /etc/hosts
```

- Add the following IPs at the end and save.
```
127.0.0.1  erp.acunetix.com
127.0.0.1  erp.acunetix.com.
::1  erp.acunetix.com
::1  erp.acunetix.com.

127.0.0.1  telemetry.invicti.com
127.0.0.1  telemetry.invicti.com.
::1  telemetry.invicti.com
::1  telemetry.invicti.com.
```

- go to Acunetix directory and open terminal

- Give executable permission to al the .sh files
```
chmod +x *.sh
```

- Now execute Acunetix 
```
./acunetix_15.3.230126173_x64.sh 
```

- Press Enter.
- Press q.
- Type yes
- keep the hostname as 'kali'
- Use any random email id: admin123@mail.com
- Password: Admin123@mail.com1

- After installation, activate license
- To do this, stop Acunetix service first
```
sudo systemctl stop acunetix
```

- Replace the license by executing:
```
 ./start.sh 
```

>>This start.sh file contains the following command:
```
sudo cp wvsc /home/acunetix/.acunetix/v_230126173/scanner/wvsc
sudo chown acunetix:acunetix /home/acunetix/.acunetix/v_230126173/scanner/wvsc
sudo chmod +x /home/acunetix/.acunetix/v_230126173/scanner/wvsc
```

- To add license, 
```
./last.sh
```

-  Start Acunetix service
```
sudo systemctl start acunetix
```

- Now go to Browser and search for 
```
https://kali:3443
```
