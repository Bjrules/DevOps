### PROJECT4 Banjo Babade  (darey.io) Devops Trainng
#### Implementation of  MEAN STACK DEPLOYMENT TO UBUNTU IN AWS
1. AWS instance ubuntu 20.04 was used
![my aws instance named SSH-CLIENT](Screenshot_20221230_120003.png)

2. tried to perform ssh-copy-id -i /home/ubuntu/.ssh/id_rsa.pub  ubuntu@MY-IP-ADDRESS **failed severally**
   ![tried to perform ssh Connection](Screenshot_20221230_135128.png)

3. sudo apt update
4. sudo apt upgrade
   
 ![Updating and upgrading ubuntu](Screenshot_20221230_160319.png)

 

[^1]: sudo apt -y install curl dirmngr apt-transport-https      lsb-release ca-certificates

[^1]: curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
![Certificates Installation](Screenshot_20221230_160530.png)

5. **Install MongoDB** sudo apt install -y mongodb
6. **Start The MongoDB server** sudo service mongodb start
7. **Check the status of the server** sudo systemctl status mongodb
8. **Node package manager installation** sudo apt install -y npm
9. **body parser installation** sudo npm install body-parser
   
    ![node instllation](Screenshot_20221230_160821.png)

    ![Node installaion](Screenshot_20221230_161312.png)
10. sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6


11. echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.4.list
    
    ![key for MongoDB](Screenshot_20221230_161604.png)

    ![MongoDB installation](Screenshot_20221230_162053.png)

![Service start and Status check](Screenshot_20221230_162309.png)

![sudo npm install body-parser](Screenshot_20221230_162837.png)

![npm init inside the Books Directory](Screenshot_20221230_163301.png)

![init setup](Screenshot_20221230_164203.png)

![curl to dump app interface on CLI](Screenshot_20221230_165115.png)

![depoyed successfully](Screenshot_20221230_172042.png)

![Entries Made](Screenshot_20221230_172641.png)
