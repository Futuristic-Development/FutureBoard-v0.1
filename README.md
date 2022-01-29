# FutureBoard-v1
A better version of dashactyl
-------------------------------------
Installation:

apt install wget && wget https://raw.githubusercontent.com/Futuristic-Development/FutureBoard-v0.1/main/installscript && chmod 600 ./installscript && bash ./installscript

-----------------------------------------

web server config:

systemctl start nginx

certbot certonly --nginx -d your.futureboard.domain

cd /etc/nginx/conf.d

touch futureboard.conf

nano futureboard.conf

then go to nginx-config


----------------------------------------

then go back to ur original folder in futureboard and run

npm install pm2 -g

pm2 start index.js

-------------------------------------------

Need help? https://discord.gg/4ncGQNt2Js
