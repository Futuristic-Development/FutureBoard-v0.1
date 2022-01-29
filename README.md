# FutureBoard-v1
A better version of dashactyl


web server config:

systemctl start nginx

certbot certonly --nginx -d your.futureboard.domain

cd /etc/nginx/conf.d

touch futureboard.conf

nano futureboard.conf

then go to nginx-config
