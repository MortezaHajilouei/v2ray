# v2ray-instalation x-ui

### installation:

```sh
sudo apt update
sudo apt upgrade -y 
sudo apt install socat -y
wget https://raw.githubusercontent.com/MortezaHajilouei/v2ray/main/install.sh
sudo bash install.sh
```


Now you can open x-ui panel with your ip addres http://[IP]:54321

# v2ray with ip limit

thanks to  [hossinasaadi]


### installation:
```sh
sudo apt update
sudo apt upgrade -y 
sudo apt install socat -y
wget https://raw.githubusercontent.com/MortezaHajilouei/v2ray/main/install-limit.sh
sudo bash install-limit.sh
```

Now you can open x-ui panel with your ip addres http://[IP]:54321
open panel settings and tab xray related settings put this to first of json :
 
 ```sh
"log": {
    "loglevel": "warning", 
    "access": "./access.log"
},
```
should be alike:

![Screenshot from 2022-11-08 12-04-21](https://user-images.githubusercontent.com/38998555/200520805-9c10d409-4e1d-46a1-8220-e269535b46c8.png)


add new config with ip limit and email for inbound(vmess)(0 = no limit)

if you had x-ui before that, pleaes open panel and press ctrl + f5 or ctrl+shift+R to clear browser cache


[hossinasaadi]: <https://github.com/hossinasaadi>

