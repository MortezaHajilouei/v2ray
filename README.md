# v2ray-instalation x-ui

installation:

sudo apt update
sudo apt upgrade -y 
sudo apt install socat -y
wget https://raw.githubusercontent.com/MortezaHajilouei/v2ray/main/install.sh
sudo bash install.sh

Now you can open x-ui panel with your ip addres http://[IP]:54321

# v2ray with ip limit

thanks to @hossinasaadi

installation:
sudo apt update
sudo apt upgrade -y 
sudo apt install socat -y
wget https://raw.githubusercontent.com/MortezaHajilouei/v2ray/main/install-limit.sh
sudo bash install-limit.sh

Now you can open x-ui panel with your ip addres http://[IP]:54321
open panel settings and tab xray related settings put this to first of json :
 
"log": {
   "loglevel": "warning", 
   "access": "./access.log"
 },
 
 

add new config with ip limit and email for inbound(vmess)(0 = no limit)

if you had x-ui before that, pleaes open panel and press ctrl + f5 or ctrl+shift+R to clear browser cache
