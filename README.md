# my-nginx-conf
This is the Nginx config that I use!


Create a new dir in /etc/nginx like my_conf. So the path of new dir will be /etc/nginx/my_conf.
Then clone this repo on that path by git clone git@github.com:ghorbani-mohammad/my-nginx-conf.git .

Change content of /etc/nginx/nginx.conf to this:
include /etc/nginx/my_conf/nginx.conf;

