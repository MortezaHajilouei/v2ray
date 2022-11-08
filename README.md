# v2ray-instalation x-ui

2. sudo apt update
3. sudo apt upgrade -y 
4. sudo apt install curl socat -y
 curl https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh --output bash.sh
6. sudo bash bash.sh

# v2ray-ip-limit

tanks to @hossinasaadi

installation:

wget https://raw.githubusercontent.com/hossinasaadi/x-ui/dev/install.sh
sudo bash install.sh

 open panel settings and tab xray related settings put this to first of json :
 
"log": {
   "loglevel": "warning", 
   "access": "./access.log"
 },
 

add new config with ip limit and email for inbound(vmess)(0 = no limit)

open panel and press ctrl + f5 or ctrl+shift+R to clear browser cache
