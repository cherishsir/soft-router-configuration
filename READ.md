###echo "# soft-router-configuration" >> README.md
###git init
###git add README.md
##i#git commit -m "first commit"
###git remote add origin https://github.com/cherishsir/soft-router-configuration.git
####git push -u origin master


###some configuraton files about my soft routers in dorm

#####fristly ,install the two software

sudo apt-get install hostapd  isc-dhcp-server

####secondly, move all these files to the  /etc/xxxx directory


###add hostapd.conf to demo  service 

sudo vim  /etc/default/hostapd


###add the inner router interface to isc-dhcp-server

sudo vim /etc/default/isc-dhcp-server




